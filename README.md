# stdgont
<p><b>Short description of the project.</b>
<p>Add Semantic Web ontology power to OpenRefine!
(Proof of concept/demonstration purposes only).
<p>Generate&use the Simplified Technical Dictionary Generic Ontology (STDGOnt) in OpenRefine operation JSON.
For example, to reconcile and enrich corporate material master data.

Introduction.
This project demonstrates a practical approach for reconciliation and enrichment of corporate material master data.
It just shows the concept and is not expected to be used in production environment.
The project is partially inspired by a series of ECCMA webinars (https://eccma.org/forms/webinar), devoted to data quality in supply chain.
There are a number of sources, explaining how material master data quality impacts business, 
and there are a number of commercial and free solutions for improving of material master data quality.
This project demonstrates another one practical approach in this area.

<p><b>Source of poor material master data quality.</b>
Explained briefly in demonstration video.

<p><b>Solution design.</b>
The proposed solution includes the following components:
<li> OpenRefine (previously Google Refine) application, https://openrefine.org/
<li> R Shiny application to generate or reuse Simplified Technical Dictionary Generic Ontology (STDGOnt) JSON files and OpenRefine operation JSON https://v1st.shinyapps.io/stdgont-app/
  <li> <a href="https://github.com/v1st-git/stdgont/">Repository to keep and exchange by STDGOnt JSON files (this repository/project)</a>
<li> Semantic Web publishing service/wrapper for SPARQL endpoint https://stdgont.uk.to/stdgont-openrefine-api-post1data
<li> Semantic Web fuzzy search service/wrapper for SPARQL endpoint https://stdgont.uk.to/stdgont-fuzzy-search-api
<li> SPARQL endpoint (internal service, is not available from Internet)

  <p><b>Three basic use cases:</b>
<li> Use OpenRefine and R Shiny STDGOnt application to create and publish STDGOnt ontology for further use in master data reconciliation and enrichment, based on fuzzy search
<li> Use R Shiny STDGOnt application to generate JSON for a set of OpenRefine operations based on STDGOnt fuzzy seach web service
<li> Use OpenRefine to get master data reconciled and structured by utilizing of JSON operations, created by R Shiny STDGOnt application

Solution demonstration video, explaining how application can be used to solve typical problem, related to material master data cleansing: https://youtube.com/watch?v=Uqsrp04erfM&feature=share
