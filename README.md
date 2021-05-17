# EpilepsyOntology

The objective of this project is to generate an Epilepsy Ontology for TextMining purpose.

## Development
- src/ontology/modules
    - contains OntoFox input files
    - manually created
- src/ontology/modules/
    - contains OntoFox output files
    - automatically generated
- src/ontology/ClinicalTrialOntology.owl
    - main devlopement file, imports module
    - manually created
- src/ontology/catalog-v001.xml
     - otege catalog file that links IRIs from impored modules to relative file paths
     - manually created
- EPO_mergde.owl
    - most recent release (merged main devlopement file with all imported modules
    - automatically generated
