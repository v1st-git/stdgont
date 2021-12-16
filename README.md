# stdgont
<p><b>Short description of the project.</b>
<p><i>Add Semantic Web ontology power to OpenRefine!</i>
<p><i>(Proof of concept/demonstration purposes only).</i>
<p>Generate&use the Simplified Technical Dictionary Generic Ontology (STDGOnt) as OpenRefine operation JSON.
<p>For example, to reconcile and enrich corporate material master data.

<p><b>Introduction.</b>
This project demonstrates a practical approach for reconciliation and enrichment of source messy data, processed by OpenRefine.
It just shows the concept and is not expected to be used in production environment.
<p>The project is partially inspired by a series of <a href="https://eccma.org/forms/webinar">ECCMA webinars</a>, devoted to data quality in supply chain.
<p>There are a number of sources, explaining how material master data quality impacts business, 
and there are a number of commercial and free solutions for improving of material master data quality.
This project demonstrates another one practical approach in this area as one of use cases.

<p><b>Source of poor material master data quality.</b>
Explained in ECCMA materials, and briefly in demonstration video.

<p><b>Solution design.</b>
The proposed solution includes the following components:
  <li> <a href="https://openrefine.org/">OpenRefine (previously Google Refine) application</a>
  <li> <a href="https://v1st.shinyapps.io/stdgont-app/">R Shiny application</a> to generate or reuse Simplified Technical Dictionary Generic Ontology (STDGOnt) JSON files and OpenRefine operation JSON 
<li> Github Repository to keep and exchange by STDGOnt JSON files <a href="https://github.com/v1st-git/stdgont/">(this repository/project)</a>
<li> <a href="https://stdgont.uk.to/stdgont-openrefine-api-post1data">Semantic Web publishing service</a>/wrapper for SPARQL endpoint 
<li> <a href="https://stdgont.uk.to/stdgont-fuzzy-search-api">Semantic Web fuzzy search service</a>/wrapper for SPARQL endpoint 
<li> <a href="https://stdgont.uk.to/stdgont-openrefine-single-recon-api">Generic OpenRefine reconciliation API</a> service (minimal set of features)
<li> <a href="https://stdgont.uk.to/stdgont-openrefine-qudt-recon-api">OpenRefine reconciliation API for QUDT units of mesurement</a> service (minimal set of features)
<li> SPARQL endpoint (internal service, is not available from Internet)

  <p><b>Three basic use cases:</b>
<li> Use OpenRefine and R Shiny STDGOnt application to create and publish STDGOnt ontology for further use in master data reconciliation and enrichment, based on fuzzy search
<li> Use R Shiny STDGOnt application to generate JSON for a set of OpenRefine operations based on STDGOnt fuzzy seach web service
<li> Use OpenRefine to get master data reconciled and structured by utilizing of JSON operations, created by R Shiny STDGOnt application

<p><a href="https://youtube.com/watch?v=Uqsrp04erfM&feature=share">Solution demonstration video</a>, explaining how the application can be used to solve typical problem, related to material master data cleansing.
<p><a href="https://youtu.be/NbZAMSR1XGc">OpenRefine reconciliation API demonstration video</a>, explaining how the application can be used to reconcile OpenRefine data column, containing Wikidata properties URI
  <p><a href="https://youtube.com/watch?v=oJi2rscsCE8&feature=share">How to use STDGOnt service video</a> - to verify and reconcile of <a href="http://linkedmodel.org/catalog/qudt/1.1/">QUDT</a> units of measurement as <a href="https://stdgont.uk.to/stdgont-openrefine-qudt-recon-api">OpenRefine/QUDT reconciliation API</a>

