Download-Transform-Merge Template
================================================
KG hub template fro tools to generate knowledge graphs for projects

Documentation
------------------------------------------------

This template could be used for data ingestion for varied sources.

**Components**

- Download: The [download.yaml](download.yaml) contains all the URLs for the source data.
- Transform: The [transform_utils](project_name/transform_utils) contains the code relevant to trnsformations of the raw data into nodes and edges (tsv format)
- Merge: Implementation of the 'merge' function from [KGX](https://github.com/biolink/kgx) using [merge.yaml](merge.yaml) as a source file.

**Utilities**

The code for these are found in the [utils](project_name/utils) folder.

- NLP using [OGER](https://github.com/OntoGene/OGER)
- [ROBOT](https://github.com/ontodev/robot) for transforming ontology.OWL to ontology.JSON


