# 2020_LooBell_NatureMedicine

This GitHub repository contains all the code used to analyse the sequencing data associated with Loo and Bell _et al._ (2020) _Nature Medicine_. This repository aims to ensure the reproducibility of our published results, and support others performing similar analyses. If you have any feedback or questions please get in touch.

Emma

## Directory structure

* code/ - _contains R Notebook(s) and the resulting HTML file(s)_
  * 00A - Sequencing read pre-processing
  * 00B - R configuration
  * RRBS_01 - Sequencing read alignment with Bismark
  * RRBS_02 - Calling base level methylation with MethylKit
  * RRBS_03 - Calculating differential methylation with MethylKit
  * RRBS_04 - Defining hypomethylated windows for HOMER motif enrichment
  * ATAC_05 - Calling nucleosome-free regions with MACS2
  * ATAC_06 - Quantifying nucleosome-free regions
  * ATAC_07 - Defining nucleosome-free regions unique to the DAC sample group for HOMER motif enrichment
  * RNA_08 - Quantifying transcript expression with Kallisto
  * RNA_09 - Calling differential transcript expression with Sleuth
  * RNA_10 - Gene-set enrichment with CensensusPathDB and limma
* data/ - _contains any data used in this project_
  * 01_raw/
  * 02_clean/
  * 03_augmented/
* docs/ - _contains any documents pertaining to this project_
  * Presentation_plan_template.docx
  * Presentation_template.pptx
  * Research_project_plan.docx
* results/ - _contains results files_
  * docs/
  * figures/
  * tables/