# CGIAR_BigData_metadata_schema
human-readable, machine-actionable flexible and extensible, ontology-independent metadata schema focused on making messy socio-economic data FAIRER

We want to Launch the metadata schema as soon as possible so we are moving forward with the OIMS metad data schema development

StructureOIMSversionBeta1_1_0.json is the version of late April 2019 but is not generic enough and is missing out some crucial details.
StructureOIMSversionBeta1_1_1.json is the version of early May 2019 and we intend to use this as the test case. This describes the metadata schema

MetaData_StructureOIMS_version_1_0.json describes StructureOIMSversionBeta1_1_1.json

MetaData_MetaData_StructureOIMS_version_1_0.json  describes  MetaData_StructureOIMS_version_1_0.json and it describes itself

This means we can describe any JSON format metadata schema using MetaData_StructureOIMS_version_1_0.json

we have a linkage file [versionlinks.json] that allows us know how these structure files are linked. We need this because it could well be that a new version of the structure files is developed and we need to know how they are linked.

# TO DO
1. not all parts of the structure files have been completed. thgis needs to be done.
2. besides the basic metadata schemas there are other metadata schemas that can be incoroporated into the system. The schema needs to be described in the generic terms though.
3. We are running into issues that there are missing ontology terms for some of our metadata fields. We can take this up with the Ontology WEG of the CGIAR Platform for Big Data in Agriculture: Marie-Angelique LaPorte and Elizabeth Arnaud.
4. We need a concordance file for metadata schema fields.
5. We need concordance file(s) for elements of controled vocabularies used in different schemas. 

# Remarks   :                                                                  
 1. Note that // as field name denotes a comment. We use this notation       
becauseJSON does not have a specific functionality for adding comments and we
feel that commenting is essential for making code transparent.               
 2. Note that we use GTREE notation to allow a structured view of the JSON   
metadata schema using the GTREE integrated development environment           
https://www.wecr.wur.nl/gamstools/index.htm                                  



# Terms of use
<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.

# Citation information
Kruseman, G., 2019. OIMS metadata schema. International Maize and Wheat Improvement Center (CIMMYT). URL: https://github.com/GideonKruseman/CGIAR_BigData_metadata_schema
