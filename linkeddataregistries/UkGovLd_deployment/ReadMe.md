# Deploying UkGovLD/registry-core

Epimorphics Docker image can be directly used.

The [Dockerfile available here]() uses it adds the Pulsar plugin. 

No need to add Pulsar plugin if you're not planning to use Pub/Sub functionalities

The application base URL being the baseURI for the registries one need to configure the resolver behaviour to ensure it does not mess with network activity.

Example in Apache mod_rewrite

~~~ 
<Location "/ncl/">
        Require all granted
        ProxyPreserveHost On
        ProxyPass http://ip_of_the_deployed_app/ncl/
        ProxyPassReverse http://ip_of_the_deployed_app/ncl/
</Location>
~~~

# Using it

The wiki of the project is highly informative and the team really reactive : https://github.com/UKGovLD/registry-core/wiki