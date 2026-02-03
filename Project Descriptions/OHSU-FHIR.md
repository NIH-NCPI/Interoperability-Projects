<img src="https://github.com/NIH-NCPI/.github/blob/main/profile/ncpi-logo-close-crop.png" width="40" alt="NCPI Logo"/> [Home](https://github.com/NCPITest)/[Interoperability Projects](https://github.com/NIH-NCPI/Interoperability-Projects/blob/main/README.md)/OHSU-FHIR

<h1> <p align=left> Connecting FHIR, the CDA, and DRS Across NIH Cloud Resources </p> </h1>

<h2> Summary </h2>

<b> PI: </b> Kyle Ellrott, PhD

<b> Institution: </b> Oregon Health & Science University

The project aims to develop a FHIR aggregator to enhance data interoperability and access across NIH consortia. By indexing FHIR endpoints, it will help researchers identify and retrieve relevant biological samples and datasets. Building on the Cancer Data Aggregator (CDA) model, it extends capabilities to non-cancer resources using a common data model. Initial efforts focus on integrating genomic and experimental data into FHIR, facilitating easier access and mapping of diverse data types, thus supporting more efficient and comprehensive biomedical research.

<h3> Scientific Aims </h3>

* Improve the understanding of rare cancer types, such as cholangiocarcinoma, by building large synthetic cohorts from multiple NIH datasets.

<h3> Technical Aims </h3>

* Develop a FHIR aggregator to aid researchers in accessing a comprehensive index of all available FHIR endpoints.
* Develop CDA/FHIR schema conversion utilities.
* Develop a FHIR endpoint to mirror CDA data.
* Extend the GA4GH DRS client to operate with Broad’s Terra data system.
* Test CDA/FHIR/DRS integration in a protected access cloud workspace.
* Combine metadata searching APIs (FHIR and CDA) with a data object retrieval API (GA4GH DRS).

<h2> Additional Project Materials </h2>

Dr. Kyle Ellrott and his team developed the FHIR Aggregator, a free tool for finding and downloading biomedical data from across the NIH. The FHIR Aggregaor includes data from Cancer Data Aggregator (CDA), Cellosaurus, Genomic Data Commons (GDC), Genotype-Tissue Expression Portal (GTEx), Human Tumor Atlas Network (HTAN), International Cancer Genome Consortiium (ICGC), and 1000 Genomes. 

More information on the FHIR Aggregator can be found [here](https://github.com/FHIR-Aggregator). 
* [FHIR Aggregator - Cloud](https://github.com/FHIR-Aggregator/cloud) provides instructions on configurations of SWAG reverse proxy to a local instance of the HAPI FHIR server and a proxy to the Google Healthcare API.
* [FHIR Aggregator Query](https://github.com/FHIR-Aggregator/fhir-aggregator-client) provides information on how to query FHIR servers for local analysis.
* [NCPI FHIR-Aggregator Query](https://fhir-aggregator.github.io/#tools) provides interactive Jupyter notebooks used in operation of locally hosted CLI tool that executes graph-based traversals across multiple interconnected FHIR graphs. 

The FHIR Aggregator currently exists in a static state, and can be found [here](https://fhir-aggregator.github.io/). A paper detailing the FHIR aggregator is in development, and a pre-print is available [here](https://www.biorxiv.org/content/10.64898/2025.12.22.695544v1). 


