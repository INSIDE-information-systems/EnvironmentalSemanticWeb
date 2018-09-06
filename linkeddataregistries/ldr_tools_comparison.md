A comparison between registry tools used for managing and publishing registers

<table cellspacing="0" border="0">
	<colgroup width="194"></colgroup>
	<colgroup width="222"></colgroup>
	<colgroup width="493"></colgroup>
	<colgroup width="267"></colgroup>
	<colgroup width="232"></colgroup>
	<tr>
		<td colspan=3 height="20" align="center" valign=middle><font color="#000000">Criteria</font></td>
		<td align="center" valign=middle><font color="#000000">Re3gistry</font></td>
		<td align="center" valign=middle><font color="#000000">ukgovld</font></td>
	</tr>
	<tr>
		<td rowspan=10 height="200" align="center" valign=middle><font color="#000000">proper linked data approach</font></td>
		<td colspan=2 align="center" valign=middle><font color="#000000">data stored in a triple store</font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
	</tr>
	<tr>
		<td align="center" valign=middle><font color="#000000">true URIs</font></td>
		<td align="center" valign=middle><font color="#000000">not mentionning the tool used</font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
	</tr>
	<tr>
		<td rowspan=2 align="center" valign=middle><font color="#000000">link to internal vocabularies</font></td>
		<td align="center" valign=middle><font color="#000000">structure and data</font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
	</tr>
	<tr>
		<td align="center" valign=middle><font color="#000000">alignment with internal vocabularies</font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
	</tr>
	<tr>
		<td rowspan=3 align="center" valign=middle><font color="#000000">link to external ontologies</font></td>
		<td align="center" valign=middle><font color="#000000">ex : W3C vocabs, ou domains</font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
	</tr>
	<tr>
		<td align="center" valign=middle><font color="#000000">alignment with external vocabularies</font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
	</tr>
	<tr>
		<td align="center" valign=middle><font color="#000000">structure and data</font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
	</tr>
	<tr>
		<td rowspan=3 align="center" valign=middle><font color="#000000">allow to add properties</font></td>
		<td align="center" valign=middle><font color="#000000">at whole register level</font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
	</tr>
	<tr>
		<td align="center" valign=middle><font color="#000000">at register item (instance) level</font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
	</tr>
	<tr>
		<td align="center" valign=middle><font color="#000000">with multiple values per properties authorized</font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
	</tr>
	<tr>
		<td rowspan=4 height="80" align="center" valign=middle><font color="#000000">register item workflow</font></td>
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
		<td rowspan=2 align="center" valign=middle><font color="#000000">notification system</font></td>
		<td align="center" valign=middle><font color="#000000">admin in the back-end (I have a new item to evaluate)</font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
	</tr>
	<tr>
		<td align="center" valign=middle><font color="#000000">external system consuming the register (RSS, Pub/Sub, ...)</font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
	</tr>
	<tr>
		<td rowspan=7 height="140" align="center" valign=middle><font color="#000000">front-ends</font></td>
		<td colspan=2 align="center" valign=middle><font color="#000000">SPARQL end-point</font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
	</tr>
	<tr>
		<td colspan=2 align="center" valign=middle><font color="#000000">RESTful APIs</font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
	</tr>
	<tr>
		<td rowspan=2 align="center" valign=middle><font color="#000000">content negociation</font></td>
		<td align="center" valign=middle><font color="#000000">serialization</font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
	</tr>
	<tr>
		<td align="center" valign=middle><font color="#000000">language</font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
	</tr>
	<tr>
		<td rowspan=3 align="center" valign=middle><font color="#000000">GUI (User interface)</font></td>
		<td align="center" valign=middle><font color="#000000">tree view</font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
	</tr>
	<tr>
		<td align="center" valign=middle><font color="#000000">form view</font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
	</tr>
	<tr>
		<td align="center" valign=middle><font color="#000000">diff mode</font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
	</tr>
	<tr>
		<td rowspan=2 height="40" align="center" valign=middle><font color="#000000">item versioning</font></td>
		<td align="center" valign=middle><font color="#000000">workflow</font></td>
		<td align="center" valign=middle><font color="#000000">never override/delete previously exposed data</font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
	</tr>
	<tr>
		<td align="center" valign=middle><font color="#000000">+ implementation in URI</font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
	</tr>
	<tr>
		<td rowspan=6 height="160" align="center" valign=middle><font color="#000000">import / export</font></td>
		<td rowspan=5 align="center" valign=middle><font color="#000000">formats</font></td>
		<td align="center" valign=middle><font color="#000000">RDF ttl</font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
	</tr>
	<tr>
		<td align="center" valign=middle><font color="#000000">RDF/XML</font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
	</tr>
	<tr>
		<td align="center" valign=middle><font color="#000000">JSON-LD</font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
	</tr>
	<tr>
		<td align="center" valign=middle><font color="#000000">csv</font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
	</tr>
	<tr>
		<td align="center" valign=middle><font color="#000000">? ISO 19135 ?</font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
	</tr>
	<tr>
		<td align="center" valign=middle><font color="#000000">from other tools (ex : Excel,...)</font></td>
		<td align="center" valign=middle><font color="#000000">for those that are not turtle hermits (https://static.comicvine.com/uploads/original/3/38919/2178068-master_roshi_and_turtle.jpg)</font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
	</tr>
	<tr>
		<td height="20" align="center" valign=middle><font color="#000000">content</font></td>
		<td colspan=2 align="center" valign=middle><font color="#000000">coherence tests across registries</font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
	</tr>
	<tr>
		<td rowspan=10 height="200" align="center" valign=middle><font color="#000000">IT</font></td>
		<td colspan=2 align="center" valign=middle><font color="#000000">tomcat version</font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
	</tr>
	<tr>
		<td rowspan=3 align="center" valign=middle><font color="#000000">community</font></td>
		<td align="center" valign=middle><font color="#000000">dev</font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
	</tr>
	<tr>
		<td align="center" valign=middle><font color="#000000">knowledgeable users</font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
	</tr>
	<tr>
		<td align="center" valign=middle><font color="#000000">user</font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
	</tr>
	<tr>
		<td colspan=2 align="center" valign=middle><font color="#000000">security (ex : Acunetix happy ?)</font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
	</tr>
	<tr>
		<td rowspan=2 align="center" valign=middle><font color="#000000">development</font></td>
		<td align="center" valign=middle><font color="#000000">status</font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
	</tr>
	<tr>
		<td align="center" valign=middle><font color="#000000">easiness to propose/commit changes</font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
	</tr>
	<tr>
		<td colspan=2 align="center" valign=middle><font color="#000000">funding</font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
	</tr>
	<tr>
		<td rowspan=2 align="center" valign=middle><font color="#000000">performances</font></td>
		<td align="center" valign=middle><font color="#000000">back-end (ex : loading big graphs)</font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
	</tr>
	<tr>
		<td align="center" valign=middle><font color="#000000">front-end (ex : multiple clients)</font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
	</tr>
	<tr>
		<td height="20" align="center" valign=middle><font color="#000000">register federation</font></td>
		<td colspan=2 align="center" valign=middle><font color="#000000">dynamic generation/edit of .ror files (INSPIRE federation)</font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
	</tr>
</table>
