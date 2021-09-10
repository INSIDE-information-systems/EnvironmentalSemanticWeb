FROM maven:3.6.3-jdk-11-openj9 as builder

WORKDIR /home

RUN apt-get update && \
	apt-get install -y git

RUN git clone --branch registry-pulsar-plugin-1.0.1 https://github.com/UKGovLD/registry-pulsar-plugin.git
RUN mvn -q -f registry-pulsar-plugin/pom.xml package -DskipTests
RUN curl https://s3-eu-west-1.amazonaws.com/ukgovld/release/com/github/ukgovld/registry-core/2.3.1/registry-core-2.3.1.war -o registry-core-2.3.1.war


FROM tomcat:9.0-jdk8
COPY --from=builder /home/registry-core-2.3.1.war /usr/local/tomcat/webapps/ncl.war
RUN unzip /usr/local/tomcat/webapps/ncl.war -d /usr/local/tomcat/webapps/ncl && \
    rm /usr/local/tomcat/webapps/ncl.war
COPY --from=builder /home/registry-pulsar-plugin/target/registry-pulsar-plugin-1.0.1-jar-with-dependencies.jar /usr/local/tomcat/webapps/ncl/WEB-INF/lib
