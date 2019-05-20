A comparison between registry tools used for managing and publishing registers

<table cellspacing="0" border="0">
	<colgroup width="253"></colgroup>
	<colgroup width="272"></colgroup>
	<colgroup width="493"></colgroup>
	<colgroup width="267"></colgroup>
	<colgroup width="319"></colgroup>
	<tr>
		<td style="border-bottom: 2px solid #000000" colspan=3 height="20" align="center" valign=middle><font color="#000000">Criteria</font></td>
		<td style="border-bottom: 2px solid #000000" align="center" valign=middle><font color="#000000">Re3gistry 1.3</font></td>
		<td style="border-bottom: 2px solid #000000" align="center" valign=middle><font color="#000000">ukgovld 2.0 SNAPSHOT</font></td>
	</tr>
	<tr>
		<td style="border-bottom: 2px solid #000000" rowspan=9 height="193" align="center" valign=middle><font color="#000000">proper linked data approach</font></td>
		<td colspan=2 align="center" valign=middle><font color="#000000">data stored in a triple store</font></td>
		<td align="center" valign=middle><font color="#000000">no</font></td>
		<td align="center" valign=middle><font color="#000000">yes</font></td>
	</tr>
	<tr>
		<td align="center" valign=middle><font color="#000000">true URIs</font></td>
		<td align="center" valign=middle><font color="#000000">not mentionning the tool used</font></td>
		<td align="center" valign=middle><font color="#000000">No. Dependent on the implementation URI  of the register</font></td>
		<td align="center" valign=middle><font color="#000000">True. independent from the implementation URI  of the register if specified on upload</font></td>
	</tr>
	<tr>
		<td rowspan=2 align="center" valign=middle><font color="#000000">link to internal vocabularies</font></td>
		<td align="center" valign=middle><font color="#000000">structure and data</font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
		<td align="center" valign=middle><font color="#000000">possible</font></td>
	</tr>
	<tr>
		<td align="center" valign=middle><font color="#000000">alignment with internal vocabularies</font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
		<td align="center" valign=middle><font color="#000000">possible,  throught context declaration</font></td>
	</tr>
	<tr>
		<td rowspan=2 align="center" valign=middle><font color="#000000">link to external vocabularies<br>(ex : W3C vocabs, or domains)</font></td>
		<td align="center" valign=middle><font color="#000000">structure and data</font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
		<td align="center" valign=middle><font color="#000000">possible, throught context definition</font></td>
	</tr>
	<tr>
		<td align="center" valign=middle><font color="#000000">alignment with external vocabularies</font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
		<td align="center" valign=middle><font color="#000000">possible</font></td>
	</tr>
	<tr>
		<td style="border-bottom: 2px solid #000000" rowspan=3 align="center" valign=middle><font color="#000000">allow to add properties</font></td>
		<td align="center" valign=middle><font color="#000000">at whole register level</font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
		<td align="center" valign=middle><font color="#000000">possible</font></td>
	</tr>
	<tr>
		<td align="center" valign=middle><font color="#000000">at register item (instance) level</font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
		<td align="center" valign=middle><font color="#000000">possible </font></td>
	</tr>
	<tr>
		<td style="border-bottom: 2px solid #000000" align="center" valign=middle><font color="#000000">with multiple values per properties authorized (ex : skos:altLabel)</font></td>
		<td style="border-bottom: 2px solid #000000" align="center" valign=middle><font color="#000000"><br></font></td>
		<td style="border-bottom: 2px solid #000000" align="center" valign=middle><font color="#000000"><br></font></td>
	</tr>
	<tr>
		<td style="border-bottom: 2px solid #000000" rowspan=4 height="78" align="center" valign=middle><font color="#000000">register and register items workflow</font></td>
		<td colspan=2 align="center" valign=middle><font color="#000000">with different status</font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
	</tr>
	<tr>
		<td colspan=2 align="center" valign=middle><font color="#000000">different user roles</font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
	</tr>
	<tr>
		<td style="border-bottom: 2px solid #000000" rowspan=2 align="center" valign=middle><font color="#000000">notification system</font></td>
		<td align="center" valign=middle><font color="#000000">admin in the back-end (I have a new item to evaluate)</font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
	</tr>
	<tr>
		<td style="border-bottom: 2px solid #000000" align="center" valign=middle><font color="#000000">external system consuming the register (RSS, Pub/Sub, ...)</font></td>
		<td style="border-bottom: 2px solid #000000" align="center" valign=middle><font color="#000000"><br></font></td>
		<td style="border-bottom: 2px solid #000000" align="center" valign=middle><font color="#000000"><br></font></td>
	</tr>
	<tr>
		<td style="border-bottom: 2px solid #000000" rowspan=8 height="154" align="center" valign=middle><font color="#000000">front-ends</font></td>
		<td colspan=2 align="center" valign=middle><font color="#000000">SPARQL end-point</font></td>
		<td align="center" valign=middle><font color="#000000">No</font></td>
		<td align="center" valign=middle><font color="#000000">Yes</font></td>
	</tr>
	<tr>
		<td colspan=2 align="center" valign=middle><font color="#000000">RESTful APIs</font></td>
		<td align="center" valign=middle><font color="#000000">yes</font></td>
		<td align="center" valign=middle><font color="#000000">yes</font></td>
	</tr>
	<tr>
		<td rowspan=2 align="center" valign=middle><font color="#000000">content negociation</font></td>
		<td align="center" valign=middle><font color="#000000">serialization (format)</font></td>
		<td align="center" valign=middle><font color="#000000">no</font></td>
		<td align="center" valign=middle><font color="#000000">yes</font></td>
	</tr>
	<tr>
		<td align="center" valign=middle><font color="#000000">language</font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
	</tr>
	<tr>
		<td style="border-bottom: 2px solid #000000" rowspan=4 align="center" valign=middle><font color="#000000">Interface web</font></td>
		<td align="center" valign=middle><font color="#000000">tree view</font></td>
		<td align="center" valign=middle><font color="#000000">no</font></td>
		<td align="center" valign=middle><font color="#000000">no</font></td>
	</tr>
	<tr>
		<td align="center" valign=middle><font color="#000000">form view</font></td>
		<td align="center" valign=middle><font color="#000000">no</font></td>
		<td align="center" valign=middle><font color="#000000">yes</font></td>
	</tr>
	<tr>
		<td align="center" valign=middle><font color="#000000">Possibility  to edit structure et content</font></td>
		<td align="center" valign=middle><font color="#000000">no</font></td>
		<td align="center" valign=middle><font color="#000000">yes</font></td>
	</tr>
	<tr>
		<td style="border-bottom: 2px solid #000000" align="center" valign=middle><font color="#000000">diff mode to see differences between 2 entries</font></td>
		<td style="border-bottom: 2px solid #000000" align="center" valign=middle><font color="#000000">no</font></td>
		<td style="border-bottom: 2px solid #000000" align="center" valign=middle><font color="#000000">no</font></td>
	</tr>
	<tr>
		<td style="border-bottom: 2px solid #000000" rowspan=3 height="58" align="center" valign=middle><font color="#000000">item versioning</font></td>
		<td align="center" valign=middle><font color="#000000">workflow</font></td>
		<td align="center" valign=middle><font color="#000000">never override/delete previously exposed data</font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
		<td align="center" valign=middle><font color="#000000">possible to delete</font></td>
	</tr>
	<tr>
		<td colspan=2 align="center" valign=middle><font color="#000000">possibility to regenerate previous versious</font></td>
		<td align="center" valign=middle><font color="#000000">possible</font></td>
		<td align="center" valign=middle><font color="#000000">partially possible</font></td>
	</tr>
	<tr>
		<td style="border-bottom: 2px solid #000000" colspan=2 align="center" valign=middle><font color="#000000">+ implementation in URI</font></td>
		<td style="border-bottom: 2px solid #000000" align="center" valign=middle><font color="#000000">yes</font></td>
		<td style="border-bottom: 2px solid #000000" align="center" valign=middle><font color="#000000">yes, on metedata URIs</font></td>
	</tr>
	<tr>
		<td style="border-bottom: 2px solid #000000" rowspan=6 height="116" align="center" valign=middle><font color="#000000">import / export</font></td>
		<td rowspan=5 align="center" valign=middle><font color="#000000">formats</font></td>
		<td align="center" valign=middle><font color="#000000">RDF ttl</font></td>
		<td align="center" valign=middle><font color="#000000">no</font></td>
		<td align="center" valign=middle><font color="#000000">yes both</font></td>
	</tr>
	<tr>
		<td align="center" valign=middle><font color="#000000">RDF/XML</font></td>
		<td align="center" valign=middle><font color="#000000">export only</font></td>
		<td align="center" valign=middle><font color="#000000">yes export</font></td>
	</tr>
	<tr>
		<td align="center" valign=middle><font color="#000000">JSON-LD</font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
		<td align="center" valign=middle><font color="#000000">yes both</font></td>
	</tr>
	<tr>
		<td align="center" valign=middle><font color="#000000">csv</font></td>
		<td align="center" valign=middle><font color="#000000">yes</font></td>
		<td align="center" valign=middle><font color="#000000">yes both (csv must be well formed for import)</font></td>
	</tr>
	<tr>
		<td align="center" valign=middle><font color="#000000">? ISO 19135 ?</font></td>
		<td align="center" valign=middle><font color="#000000">yes</font></td>
		<td align="center" valign=middle><font color="#000000">no</font></td>
	</tr>
	<tr>
		<td style="border-bottom: 2px solid #000000" colspan=2 align="center" valign=middle><font color="#000000">from other tools (ex : Excel,...)<br>for those that are not turtle hermits (https://static.comicvine.com/uploads/original/3/38919/2178068-master_roshi_and_turtle.jpg)</font></td>
		<td style="border-bottom: 2px solid #000000" align="center" valign=middle><font color="#000000"><br></font></td>
		<td style="border-bottom: 2px solid #000000" align="center" valign=middle><font color="#000000">no</font></td>
	</tr>
	<tr>
		<td style="border-bottom: 2px solid #000000" rowspan=2 height="39" align="center" valign=middle><font color="#000000">content</font></td>
		<td colspan=2 align="center" valign=middle><font color="#000000">coherence tests between registries entities - test on libellé… to avoid duplicate</font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
		<td align="center" valign=middle><font color="#000000">checked on the @id level only</font></td>
	</tr>
	<tr>
		<td style="border-bottom: 2px solid #000000" colspan=2 align="center" valign=middle><font color="#000000">Importing a new registre =&gt; Comparison of the structures  of the entities of other registries before import /statut  changement …</font></td>
		<td style="border-bottom: 2px solid #000000" align="center" valign=middle><font color="#000000"><br></font></td>
		<td style="border-bottom: 2px solid #000000" align="center" valign=middle><font color="#000000">not provided</font></td>
	</tr>
	<tr>
		<td style="border-bottom: 2px solid #000000" rowspan=10 height="270" align="center" valign=middle><font color="#000000">IT</font></td>
		<td colspan=2 align="center" valign=middle><font color="#000000">tomcat version</font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
		<td align="center" valign=middle><font color="#000000">V7 for this version</font></td>
	</tr>
	<tr>
		<td rowspan=3 align="center" valign=middle><font color="#000000">community</font></td>
		<td align="center" valign=middle><font color="#000000">dev</font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
		<td align="center" valign=middle><font color="#000000">Github source + wiki maintained by Epimorphics</font></td>
	</tr>
	<tr>
		<td align="center" valign=middle><font color="#000000">knowledgeable users (ex : those posting on GitHub)</font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
		<td align="center" valign=middle><font color="#000000">active following and issue tracking from users</font></td>
	</tr>
	<tr>
		<td align="center" valign=middle><font color="#000000">user</font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
		<td align="center" valign=middle><font color="#000000">ex: CSIRO, </font></td>
	</tr>
	<tr>
		<td colspan=2 align="center" valign=middle><font color="#000000">security (ex : Acunetix happy ?)</font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
		<td align="center" valign=middle><font color="#000000">yes, according to latest tests</font></td>
	</tr>
	<tr>
		<td rowspan=2 align="center" valign=middle><font color="#000000">development</font></td>
		<td align="center" valign=middle><font color="#000000">status</font></td>
		<td align="center" valign=middle><font color="#000000">new versions realesed</font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
	</tr>
	<tr>
		<td align="center" valign=middle><font color="#000000">easiness to propose/commit changes</font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
		<td align="center" valign=middle><font color="#000000">Throught Github issues and merge requests+ direct contact with dev team</font></td>
	</tr>
	<tr>
		<td colspan=2 align="center" valign=middle><font color="#000000">funding</font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
		<td align="center" valign=middle><font color="#000000">Epimorphics --&gt; big changes request fundings from users</font></td>
	</tr>
	<tr>
		<td style="border-bottom: 2px solid #000000" rowspan=2 align="center" valign=middle><font color="#000000">performances</font></td>
		<td align="center" valign=middle><font color="#000000">back-end (ex : loading big graphs)</font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
		<td align="center" valign=middle><font color="#000000">depends on the machine configuration, tha fact that the data is RDFized and stored in triple stores must be taken ito account</font></td>
	</tr>
	<tr>
		<td style="border-bottom: 2px solid #000000" align="center" valign=middle><font color="#000000">front-end (ex : multiple clients)</font></td>
		<td style="border-bottom: 2px solid #000000" align="center" valign=middle><font color="#000000"><br></font></td>
		<td style="border-bottom: 2px solid #000000" align="center" valign=middle><font color="#000000">yet to be tested</font></td>
	</tr>
	<tr>
		<td style="border-bottom: 2px solid #000000" height="20" align="center" valign=middle><font color="#000000">register federation</font></td>
		<td style="border-bottom: 2px solid #000000" colspan=2 align="center" valign=middle><font color="#000000">dynamic generation/edit of .ror files (INSPIRE federation)</font></td>
		<td style="border-bottom: 2px solid #000000" align="center" valign=middle><font color="#000000">yes</font></td>
		<td style="border-bottom: 2px solid #000000" align="center" valign=middle><font color="#000000">not provided</font></td>
	</tr>
</table>
