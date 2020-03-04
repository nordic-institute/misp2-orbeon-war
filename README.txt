==== Orbeon MISP2 jaoks ====

==== uue war-i kompileerimine ====
Lisada <ORBEON.ZIP> fail projekti juurkausta.
Asendada faili nimi build.xml failis real <unzip src="<ORBEON.ZIP faili nimi>" dest="${build.dir}">.

K�ivitada:
ant war

war targeti tulemus: fail orbeon-misp2.war build kataloogis.


==== Datatable =====
datatable.css and datatable.xsl have been copied from eesti.ee orbeon component and slightly altered ("Forward", "Back") pagination button structure.
The rest of the datatable files have been copied from orbeon 4.4 private and public resource JAR files.
Datatable components are in folders:
custom/config/ops/yui/datatable
custom/xbl/orbeon/datatable

The altered datatable styles are added to MISP2 WebContent/resources/EE/css/xforms-ebmedded.css
In datatable.xsl, replace all xs: namespaces with xsd