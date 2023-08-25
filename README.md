# JSON_mapping_examples

Example JSON mapping files for DRaFT, MAST-U, and JET Summary  
Should only be used as an example and should not be taken as final  
Mapping files and JSON mapping plugin is still in development

### DRaFT
Example Magnetics IDS mapping file and globals, also includes DRaFT data examples itself

DRAFT_JSON is the plugin name responsible for data access of DRaFT data  
Data directory contains fake Tokamak data in JSON format for testing purposes

### MAST-U
Example Magnetics IDS mapping file and globals  

MAST-U data is retrieved using UDA::get and the GEOM plugin, this is reflected in the mapping file

### JET
Example Summary IDS mapping file and globals for CPF data from JET

JETCPF_Reader is the name of the plugin created to read JET CPF data when it is available
