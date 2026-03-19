<img src="https://github.com/NIH-NCPI/.github/blob/main/profile/ncpi-logo-close-crop.png" width="40" alt="NCPI Logo"/> [Home](https://github.com/NIH-NCPI)/[Interoperability Projects](https://github.com/NIH-NCPI/Interoperability-Projects/blob/main/README.md)/CHOP-dbGaP-KFDRC

<h1> <p align=left> Facilitating understanding of shared disease mechanisms leveraging interoperability standards across dbGaP-SRA, ImmPort, and Kids First DRC </p> </h1>

<h2> Summary </h2>
<b> PI:</b> Allison Heath, PhD

<b> Institution: </b> Children's Hospital of Philadelphia

The project focuses on enhancing data interoperability to study shared disease mechanisms by integrating phenotypic and genomic data from Kids First, the Undiagnosed Disease Network (UDN), dbGaP, and ImmPort. Utilizing the FHIR standard, the project aims to harmonize data representation and facilitate integration into the CAVATICA environment for downstream analysis. The project will address challenges such as inconsistent metadata and genomic data size by developing DRS and FHIR resources for data search, access, and analysis. By leveraging FHIR to query and integrate data from multiple sources, the project aims to streamline the analysis of genetic and environmental factors, supporting more comprehensive and efficient research.


<h3> Scientific Aims </h3>

* Analyze ImmPort asthma data to generate genomic variants of interest.
* Identify genetic variants associated with increased asthma severity in children and differences between ethnic populations within the urban pediatric cohort.
* Determine the contribution of specific environmental exposures (allergens, air pollutants, tobacco smoke) to asthma severity in children.
* Investigate gene-environment interactions that modulate the risk of asthma severity in children, identifying specific genetic variants and environmental factors involved.

<h3> Technical Aims </h3>

* Integrate KFDRC, dbGaP, and ImmPort data with CAVATICA for standardized FHIR data ingestion and expand data representation use cases.
* Provide a programmatic connection between FHIR services and DRS URIs.
* Integrate DRS endpoints with CAVATICA.
* Coordinate with KFDRC/dbGaP to provision the URECA dataset metadata and phenotypic data in a FHIR implementation interoperable with UDN and KFDRC representations.

<h3> Project Results and Accomplishments </h3>

More information on scientific use cases and experience with interoperability can be found [here](https://cavatica.sbgenomics.com/u/pamelanluna/bcm-udn) and [here](https://cavatica.sbgenomics.com/u/reuben.sarwal/dbgap-trial). <br>
The Kid's First FHIR server with adjustments for better shared adjustments with ImmPort and dbGaP can be found [here](https://fhir.kidsfirstdrc.org/) and [here](https://ncpi-api-fhir-service-dev.kf-strides.org/). <br>
The NCPI FHIR Implementation Guide Version 2 (IGv2) can be found [here](https://nih-ncpi.github.io/ncpi-fhir-ig-2/). <br>
Mapping of FHIR R4 and R5 implementations by usage across KFDRC, ImmPort, and dbGaP can be found [here](https://docs.google.com/spreadsheets/d/15vEi2QbvY5A3beuVKstmL2tQJ98zmjcaoUQFZEl9AKg/edit?gid=0#gid=0).

At NCPI's Fall 2025 workshop, Dr. Heath and Dr. Surya Saha presented the two use cases within their project work, and demonstrated connecting FHIR with DRS files in CAVATICA, enabling interoperability between platforms. A [recording of this demonstration](https://www.youtube.com/watch?v=AvG2mu5KtTw) can be found on NCPI's YouTube page. 
