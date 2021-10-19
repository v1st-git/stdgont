# stdgont
Short description of the project.
Generate&use the Simplified Technical Dictionary Generic Ontology (STDGOnt) in OpenRefine operation JSON.

Introduction.
This project demonstrates a practical approach for reconciliation and enrichment of corporate material master data.
It just shows the concept and is not expected to be used in production environment.
The project is partially inspired by a series of ECCMA webinars (https://eccma.org/forms/webinar), devoted to data quality in supply chain.
There are a number of sources, explaining how material master data quality impacts business, 
and there are a number of commercial and free solutions for improving of material master data quality.
This project demonstrates another one practical approach in this area.

Source of poor material master data quality.
To be explained.

Solution design.
The proposed solution includes the following components:
- OpenRefine (previously Google Refine) application, https://openrefine.org/
- R Shiny application to generate or reuse Simplified Technical Dictionary Generic Ontology (STDGOnt) JSON files and OpenRefine operation JSON 
- Repository to keep and exchange by STDGOnt JSON files (this repository/project)
- Semantic Web publishing service/wrapper for SPARQL endpoint
- Semantic Web fuzzy search service/wrapper for SPARQL endpoint
- SPARQL endpoint

Three basic use cases:
- Use OpenRefine and R Shiny STDGOnt application to create and publish STDGOnt ontology for futher use in master data reconciliation and enrichment, based on fuzzy search
- Use R Shiny STDGOnt application to generate JSON for a set of OpenRefine operations based on STDGOnt fuzzy seach web service
- Use OpenRefine to get master data reconciled and structured by utilizing of JSON operations, created by R Shiny STDGOnt application

Solution demonstration video.
To be created.
