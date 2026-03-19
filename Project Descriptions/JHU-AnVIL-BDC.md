<img src="https://github.com/NIH-NCPI/.github/blob/main/profile/ncpi-logo-close-crop.png" width="40" alt="NCPI Logo"/> [Home](https://github.com/NIH-NCPI)/[Interoperability Projects](https://github.com/NIH-NCPI/Interoperability-Projects/blob/main/README.md)/JHU-AnVIL-BDC


# <p align=left> AnVIL-BioData Catalyst interoperability project to leverage GTEx, T2T and HPRC to study rare genetic variants in TOPMed cohorts with deep phenotype data, whole genome sequence data, and RNA-sequence data </p>



<h2> Summary </h2> 
<b> PI: </b> Michael C. Schatz, PhD <br> 

<b> Institution: </b> Johns Hopkins University <br> 

The AnVIL-BioData Catalyst Interoperability Project focuses on integrating GTEx, T2T, and HPRC datasets to improve the study of rare genetic variants within TOPMed cohorts. The project involves utilizing the Watershed probabilistic model to identify rare variants and reprocessing datasets with the T2T reference genome to discover new variants. Additionally, the project will perform preliminary testing with the Human Pangenome Reference and assess the trait impact of these rare variants using harmonized phenotypes in BDC for TOPMed. A key component of the project is dockerizing the Watershed model and associated pipelines for use by other research groups. This will enhance the analysis of structural variants and streamline data integration, making it easier for researchers to leverage these comprehensive datasets and identify rare variants.  

<h3>Scientific Aims</h3>

* Utilize the cloud-ready Watershed to identify rare variants in the GTEx and TOPMed datasets.
* Re-analysis of TOPMed and GTEx datasets, utilizing new references including the comprehensive T2T and HPRC references, to improve the precision in alignments, variant calling, and RNA quantification.
* Assess the rare variants' impact through phenotype analysis of TOPMed, UK BioBank, and NIH All of Us data.

<h3> Technical Aims </h3>

* Enhance analytical capabilities by developing workflows that merge GTEx with TOPMed data.
* Cloud adapt the Watershed model making it suitable for application.

<h3> Project Accomplishments </h3>

Over the past year, a major focus of the project team was the development, testing, and publication of Watershed-SV, a machine learning method for identifying functional structural variants. The Watershed-SV Model can be found [here](https://github.com/jasonbhn/Watershed-SV). This model expands the original Watershed, also called Watershed-SNV, to mopdel the impact of rare structural variants (SVs) on nearby gene expression outliers. <br>

Watershed-SV was trained using matched DNA and RNA datasets from GTEx, and applied to a clinical cohort from the Undiagnosed Disease Network, leading to the discovery of compound heterozygus deletions likely causing a rare neurodevelopmental disorder. The publication detailing this can be found [here](https://pubmed.ncbi.nlm.nih.gov/40113264/). <br>

The project team created featured workspaces for both Watershed and Watershed-SV, demonstrating their use with 1000 Genomes and MAGE datasets, which are available on Terra. Workflows for both models are also available on Dockstore. 

**Watershed:** [Workspace](https://anvil.terra.bio/#workspaces/nccpi-rti-P01-002-JHU-TERRA/Watershed-SNV-MAGE) - [Workflow](https://www.dockstore.org/workflows/github.com/schatzlab/Watershed-SNV-WDL/Watershed-SNV:main?tab=info) <br>
**Watershed-SV:** [Workspace](https://anvil.terra.bio/#workspaces/nccpi-rti-P01-002-JHU-TERRA/Watershed-SV-MAGE) - [Workflow](https://www.dockstore.org/workflows/github.com/jasonbhn/Watershed-SV/Watershed-SV:WDL?tab=info)

At NCPI's Fall 2025 Workshop, Dr. Schatz gave a demonstration of Watershed, and walked through the process of finding data, using the Watershed pipelines, and data analysis in AnVIL and BDC. A [recording of this demonstration](https://www.youtube.com/watch?v=-ry91cDRVwI) can be found on NCPI's YouTube page. 




 
