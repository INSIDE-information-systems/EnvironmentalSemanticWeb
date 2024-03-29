A comparison between registry tools used for managing and publishing registers

<table cellspacing="0" border="0">
	<colgroup width="164"></colgroup>
	<colgroup width="323"></colgroup>
	<colgroup width="277"></colgroup>
	<colgroup width="326"></colgroup>
	<colgroup width="343"></colgroup>
	<tr>
		<td style="border-bottom: 2px solid #000000" colspan=3 height="20" align="center" valign=middle><font color="#000000">Critères</font></td>
		<td style="border-bottom: 2px solid #000000" align="center" valign=middle><font color="#000000">Re3gistry 1.3</font></td>
		<td style="border-bottom: 2px solid #000000" align="center" valign=middle><font color="#000000">ukgovld 2.0</font></td>
	</tr>
	<tr>
		<td style="border-bottom: 2px solid #000000" rowspan=9 height="327" align="center" valign=middle><font color="#000000"><br>approche linked data</font></td>
		<td colspan=2 align="center" valign=middle><font color="#000000">données stockées dans un triple store</font></td>
		<td align="center" valign=middle><font color="#000000">non</font></td>
		<td align="center" valign=middle><font color="#000000">oui, requetable en Sparql</font></td>
	</tr>
	<tr>
		<td align="center" valign=middle><font color="#000000">vraie URIs</font></td>
		<td align="center" valign=middle><font color="#000000">ne mentionnant pas l'outil utilisé</font></td>
		<td align="center" valign=middle><font color="#000000">Non. Dependentes sur l'URI d'implementation du registre</font></td>
		<td align="center" valign=middle><font color="#000000">Vraies URIs. Si spécifié dans les fichiers chargés, les URIs sont independentes de l'URI d'implementation du registre </font></td>
	</tr>
	<tr>
		<td rowspan=2 align="center" valign=middle><font color="#000000">lien vers des vocabulaires internes</font></td>
		<td align="center" valign=middle><font color="#000000">structure et données</font></td>
		<td align="center" valign=middle><font color="#000000">oui, vers des données seulement</font></td>
		<td align="center" valign=middle><font color="#000000">possible,  par des propriétés de matching</font></td>
	</tr>
	<tr>
		<td align="center" valign=middle><font color="#000000">alignement avec les vocabulaires internes</font></td>
		<td align="center" valign=middle><font color="#000000">non</font></td>
		<td align="center" valign=middle><font color="#000000">possible,  les ontolgies/vocabulaires utilisés localement peuvent être alignés</font></td>
	</tr>
	<tr>
		<td rowspan=2 align="center" valign=middle><font color="#000000">lien vers des vocabulaires externes <br>(ex : W3C, ou domaines)</font></td>
		<td align="center" valign=middle><font color="#000000">structure et données</font></td>
		<td align="center" valign=middle><font color="#000000">oui, vers des données seulement</font></td>
		<td align="center" valign=middle><font color="#000000">possible,  par des propriétés de matching</font></td>
	</tr>
	<tr>
		<td align="center" valign=middle><font color="#000000">alignement avec les vocabulaires externes</font></td>
		<td align="center" valign=middle><font color="#000000">non</font></td>
		<td align="center" valign=middle><font color="#000000">possible,   les ontolgies/vocabulaires utilisées localement peuvent être alignés avec des ontologies/vocabulaires externes</font></td>
	</tr>
	<tr>
		<td style="border-bottom: 2px solid #000000" rowspan=3 align="center" valign=middle><font color="#000000">possibilité d'ajouter des propriétés</font></td>
		<td align="center" valign=middle><font color="#000000">au niveau d'un registre</font></td>
		<td align="center" valign=middle><font color="#000000">pas clair (seulement une partie est affichée, qu'est il fait du reste).</font></td>
		<td align="center" valign=middle><font color="#000000">possible, par une mise à jour (partielle) de tout son contenu</font></td>
	</tr>
	<tr>
		<td align="center" valign=middle><font color="#000000">au niveau de chaque entrée (intance) d'un registre </font></td>
		<td align="center" valign=middle><font color="#000000">impossible</font></td>
		<td align="center" valign=middle><font color="#000000">possible, par le formulaire d'edition ou par le chargement d'un fichier de MAJ </font></td>
	</tr>
	<tr>
		<td style="border-bottom: 2px solid #000000" align="center" valign=middle><font color="#000000">permettre les valeurs multiples pour une propriété (ex : skos:altLabel)</font></td>
		<td style="border-bottom: 2px solid #000000" align="center" valign=middle><font color="#000000">pas testé (car seulement l'import csv supporté -&gt; peut être via séparateurs spéciaux)</font></td>
		<td style="border-bottom: 2px solid #000000" align="center" valign=middle><font color="#000000">possible</font></td>
	</tr>
	<tr>
		<td style="border-bottom: 2px solid #000000" rowspan=4 height="135" align="center" valign=middle><font color="#000000">workflow de mise à jour des registres et de leurs entrées</font></td>
		<td colspan=2 align="center" valign=middle><font color="#000000">avec différents status</font></td>
		<td align="center" valign=middle><font color="#000000">non (apparemment vu dans la 2.0)</font></td>
		<td align="center" valign=middle><font color="#000000">évolution possible des status, pour tout le registre ou pour chaque entrée</font></td>
	</tr>
	<tr>
		<td colspan=2 align="center" valign=middle><font color="#000000">avec différents rôles</font></td>
		<td align="center" valign=middle><font color="#000000">non (apparemment vu dans la 2.0)</font></td>
		<td align="center" valign=middle><font color="#000000">oui</font></td>
	</tr>
	<tr>
		<td style="border-bottom: 2px solid #000000" rowspan=2 align="center" valign=middle><font color="#000000">système de notification</font></td>
		<td align="center" valign=middle><font color="#000000">pour l'adminsitrateur du contenu (ex : j'ai une nouvelle entrée à évaluer)</font></td>
		<td align="center" valign=middle><font color="#000000">non</font></td>
		<td align="center" valign=middle><font color="#000000">non</font></td>
	</tr>
	<tr>
		<td style="border-bottom: 2px solid #000000" align="center" valign=middle><font color="#000000">pour les systèmes externes consomant le registre (RSS, Pub/Sub, ...)</font></td>
		<td style="border-bottom: 2px solid #000000" align="center" valign=middle><font color="#000000">non</font></td>
		<td style="border-bottom: 2px solid #000000" align="center" valign=middle><font color="#000000">non</font></td>
	</tr>
	<tr>
		<td style="border-bottom: 2px solid #000000" rowspan=8 height="193" align="center" valign=middle><font color="#000000">front-ends</font></td>
		<td colspan=2 align="center" valign=middle><font color="#000000">SPARQL end-point</font></td>
		<td align="center" valign=middle><font color="#000000">non</font></td>
		<td align="center" valign=middle><font color="#000000">oui</font></td>
	</tr>
	<tr>
		<td colspan=2 align="center" valign=middle><font color="#000000">RESTful APIs</font></td>
		<td align="center" valign=middle><font color="#000000">oui</font></td>
		<td align="center" valign=middle><font color="#000000">oui</font></td>
	</tr>
	<tr>
		<td rowspan=2 align="center" valign=middle><font color="#000000">négociation de contenu</font></td>
		<td align="center" valign=middle><font color="#000000">serialisation (format)</font></td>
		<td align="center" valign=middle><font color="#000000">non</font></td>
		<td align="center" valign=middle><font color="#000000">oui</font></td>
	</tr>
	<tr>
		<td align="center" valign=middle><font color="#000000">langage</font></td>
		<td align="center" valign=middle><font color="#000000">non</font></td>
		<td align="center" valign=middle><font color="#000000">oui pour le contenu, internationalisation en cours pour la GUI</font></td>
	</tr>
	<tr>
		<td style="border-bottom: 2px solid #000000" rowspan=4 align="center" valign=middle><font color="#000000">GUI (User interface)</font></td>
		<td align="center" valign=middle><font color="#000000">représentation arborescente</font></td>
		<td align="center" valign=middle><font color="#000000">non</font></td>
		<td align="center" valign=middle><font color="#000000">oui</font></td>
	</tr>
	<tr>
		<td align="center" valign=middle><font color="#000000">représentation 'formulaire'</font></td>
		<td align="center" valign=middle><font color="#000000">non</font></td>
		<td align="center" valign=middle><font color="#000000">oui</font></td>
	</tr>
	<tr>
		<td align="center" valign=middle><font color="#000000">Possibilité  d'éditer structure et contenu</font></td>
		<td align="center" valign=middle><font color="#000000">non</font></td>
		<td align="center" valign=middle><font color="#000000">oui</font></td>
	</tr>
	<tr>
		<td style="border-bottom: 2px solid #000000" align="center" valign=middle><font color="#000000">mode diff pour voir les différences entre 2 versions d'une entrée</font></td>
		<td style="border-bottom: 2px solid #000000" align="center" valign=middle><font color="#000000">non</font></td>
		<td style="border-bottom: 2px solid #000000" align="center" valign=middle><font color="#000000">non</font></td>
	</tr>
	<tr>
		<td style="border-bottom: 2px solid #000000" rowspan=3 height="78" align="center" valign=middle><font color="#000000">gestion des versions</font></td>
		<td align="center" valign=middle><font color="#000000">workflow</font></td>
		<td align="center" valign=middle><font color="#000000">ne jamais écraser / supprimer des données préalablement exposées</font></td>
		<td align="center" valign=middle><font color="#000000">pas testé / pas clair (cf chargement uniquement csv)</font></td>
		<td align="center" valign=middle><font color="#000000">oui (mais possiblité de supprimer en tant que super Admin)</font></td>
	</tr>
	<tr>
		<td colspan=2 align="center" valign=middle><font color="#000000">permet de regénerer une ancienne version</font></td>
		<td align="center" valign=middle><font color="#000000">possible</font></td>
		<td align="center" valign=middle><font color="#000000">oui</font></td>
	</tr>
	<tr>
		<td style="border-bottom: 2px solid #000000" colspan=2 align="center" valign=middle><font color="#000000">+ implementation dans les URI</font></td>
		<td style="border-bottom: 2px solid #000000" align="center" valign=middle><font color="#000000">oui</font></td>
		<td style="border-bottom: 2px solid #000000" align="center" valign=middle><font color="#000000">oui (via metadata entries URIs)</font></td>
	</tr>
	<tr>
		<td style="border-bottom: 2px solid #000000" rowspan=6 height="135" align="center" valign=middle><font color="#000000">import / export</font></td>
		<td rowspan=5 align="center" valign=middle><font color="#000000">formats</font></td>
		<td align="center" valign=middle><font color="#000000">RDF ttl</font></td>
		<td align="center" valign=middle><font color="#000000">non</font></td>
		<td align="center" valign=middle><font color="#000000">oui pour les deux opérations</font></td>
	</tr>
	<tr>
		<td align="center" valign=middle><font color="#000000">RDF/XML</font></td>
		<td align="center" valign=middle><font color="#000000">export seulement</font></td>
		<td align="center" valign=middle><font color="#000000">oui pour l'export</font></td>
	</tr>
	<tr>
		<td align="center" valign=middle><font color="#000000">JSON-LD</font></td>
		<td align="center" valign=middle><font color="#000000">non (json seulement et pour export)</font></td>
		<td align="center" valign=middle><font color="#000000">oui pour les deux opérations</font></td>
	</tr>
	<tr>
		<td align="center" valign=middle><font color="#000000">csv</font></td>
		<td align="center" valign=middle><font color="#000000">oui</font></td>
		<td align="center" valign=middle><font color="#000000">oui pour les deux opérations (le csv doit être bien formé)</font></td>
	</tr>
	<tr>
		<td align="center" valign=middle><font color="#000000">? ISO 19135 ?</font></td>
		<td align="center" valign=middle><font color="#000000">oui</font></td>
		<td align="center" valign=middle><font color="#000000">non</font></td>
	</tr>
	<tr>
		<td style="border-bottom: 2px solid #000000" colspan=2 align="center" valign=middle><font color="#000000">depuis d'autres outils (ex : Excel,...)<br>for those that are not turtle hermits (https://static.comicvine.com/uploads/original/3/38919/2178068-master_roshi_and_turtle.jpg)</font></td>
		<td style="border-bottom: 2px solid #000000" align="center" valign=middle><font color="#000000">non</font></td>
		<td style="border-bottom: 2px solid #000000" align="center" valign=middle><font color="#000000">oui (outil CSIRO existant, partiellement testé)</font></td>
	</tr>
	<tr>
		<td style="border-bottom: 2px solid #000000" rowspan=2 height="60" align="center" valign=middle><font color="#000000">contenu</font></td>
		<td colspan=2 align="center" valign=middle><font color="#000000">test de cohérence entre entrée du registre - test sur libellé… pour éviter les doublons</font></td>
		<td align="center" valign=middle><font color="#000000">pas testé</font></td>
		<td align="center" valign=middle><font color="#000000">vérification de l' @id seulement</font></td>
	</tr>
	<tr>
		<td style="border-bottom: 2px solid #000000" colspan=2 align="center" valign=middle><font color="#000000">Import d'un registre =&gt; Comparaison structures et entrées des autres registres avant import / changement statut…</font></td>
		<td style="border-bottom: 2px solid #000000" align="center" valign=middle><font color="#000000">pas testé</font></td>
		<td style="border-bottom: 2px solid #000000" align="center" valign=middle><font color="#000000">en cours de developpement pour BRGM</font></td>
	</tr>
	<tr>
		<td style="border-bottom: 2px solid #000000" rowspan=10 height="404" align="center" valign=middle><font color="#000000">IT</font></td>
		<td colspan=2 align="center" valign=middle><font color="#000000">tomcat version</font></td>
		<td align="center" valign=middle><font color="#000000"><br></font></td>
		<td align="center" valign=middle><font color="#000000">V8+ pour ce release</font></td>
	</tr>
	<tr>
		<td rowspan=3 align="center" valign=middle><font color="#000000">communauté</font></td>
		<td align="center" valign=middle><font color="#000000">de développeurs</font></td>
		<td align="center" valign=middle><font color="#000000">1 dev JRC</font></td>
		<td align="center" valign=middle><font color="#000000">Github source + wiki maintenu par Epimorphics (anciens groupes W3C linked data, apache JENA, …)</font></td>
	</tr>
	<tr>
		<td align="center" valign=middle><font color="#000000">d'utilisateurs avancés users (ex : ceux qui postent sur GitHub)</font></td>
		<td align="center" valign=middle><font color="#000000">quelques (2-3) état membres testant déploiement pour INSPIRE</font></td>
		<td align="center" valign=middle><font color="#000000">suivi acti par les utilisateurs (Github issues): Simon Cox, Rob Atkinson, Jeremy Tandy, Steve Richard, Nicolas Car….</font></td>
	</tr>
	<tr>
		<td align="center" valign=middle><font color="#000000">utilisateurs</font></td>
		<td align="center" valign=middle><font color="#000000">quelques (2-3) état membres testant déploiement pour INSPIRE</font></td>
		<td align="center" valign=middle><font color="#000000">ex: CSIRO, WMO, OGC NA, UK metoffice, uk defra/food, NOAA…</font></td>
	</tr>
	<tr>
		<td colspan=2 align="center" valign=middle><font color="#000000">security (ex : Acunetix happy ?)</font></td>
		<td align="center" valign=middle><font color="#000000">oui, selon les derniers tests </font></td>
		<td align="center" valign=middle><font color="#000000">oui</font></td>
	</tr>
	<tr>
		<td rowspan=2 align="center" valign=middle><font color="#000000">développement</font></td>
		<td align="center" valign=middle><font color="#000000">statut</font></td>
		<td align="center" valign=middle><font color="#000000">nouvelle version dispo prochainement</font></td>
		<td align="center" valign=middle><font color="#000000">continu</font></td>
	</tr>
	<tr>
		<td align="center" valign=middle><font color="#000000">facilité de proposer / committer des changement</font></td>
		<td align="center" valign=middle><font color="#000000">pas de communauté existante. Tentative JRC d'en créer une depuis la semaine du 3/09/2018</font></td>
		<td align="center" valign=middle><font color="#000000">Par Github:  &quot;issues&quot; et demande de &quot;merge&quot;+ contacte direct avec l'équipe de Dev</font></td>
	</tr>
	<tr>
		<td colspan=2 align="center" valign=middle><font color="#000000">financement</font></td>
		<td align="center" valign=middle><font color="#000000">JRC seulement -&gt; 2020 théoriquement. Appels aux états membres pour rejoindre le mouvement</font></td>
		<td align="center" valign=middle><font color="#000000">différents projets Epimorphics (uk gov, ….), évolutions CSIRO, …. --&gt; un grand changement nécessitera un financement par les utilisateurs comme tout outils open source</font></td>
	</tr>
	<tr>
		<td style="border-bottom: 2px solid #000000" rowspan=2 align="center" valign=middle><font color="#000000">performances</font></td>
		<td align="center" valign=middle><font color="#000000">back-end (ex : chargement de gros graphs de données)</font></td>
		<td align="center" valign=middle><font color="#000000">pas testé</font></td>
		<td align="center" valign=middle><font color="#000000">depend de la configuration du serveur, le fait que les données sont transformées en RDF avant d'être stoqué en triple store doit être pris en compte</font></td>
	</tr>
	<tr>
		<td style="border-bottom: 2px solid #000000" align="center" valign=middle><font color="#000000">front-end (ex : gestion charge quand clients multiples)</font></td>
		<td style="border-bottom: 2px solid #000000" align="center" valign=middle><font color="#000000">pas testé</font></td>
		<td style="border-bottom: 2px solid #000000" align="center" valign=middle><font color="#000000">utilisés dans de nombreuses infrastructures en production (cf liste communautés plus haut)</font></td>
	</tr>
	<tr>
		<td style="border-bottom: 2px solid #000000" height="20" align="center" valign=middle><font color="#000000">fédération de registres</font></td>
		<td style="border-bottom: 2px solid #000000" colspan=2 align="center" valign=middle><font color="#000000">génération/mise à jour dynamique de fichiers .ror (fédération de registre INSPIRE )</font></td>
		<td style="border-bottom: 2px solid #000000" align="center" valign=middle><font color="#000000">non</font></td>
		<td style="border-bottom: 2px solid #000000" align="center" valign=middle><font color="#000000">non, en cours de mise en place BRGM/Epimorphics</font></td>
	</tr>
</table>
