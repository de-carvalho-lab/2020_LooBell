# 2020_LooBell_NatureMedicine

This GitHub repository contains all the code used to analyse the sequencing data associated with Loo and Bell _et al._ (2020) submitted to _Nature Medicine_. This repository aims to ensure the reproducibility of our results, and support others performing similar analyses. If you have any feedback or questions please get in touch.

Emma

## Directory structure

* code/ - _contains R Notebook(s) and the resulting HTML file(s)_
  * 00A - Sequencing read pre-processing
  * 00B - R configuration
  * RRBS_01 - Sequencing read alignment with Bismark
  * RRBS_02 - Calling base level methylation with MethylKit
  * RRBS_03 - Calculating differential methylation with MethylKit
  * ATAC_04 - Calling nucleosome-free regions with MACS2
  * ATAC_05 - Quantifying nucleosome-free regions
  * ATAC_06 - Defining nucleosome-free regions unique to the DAC sample group for HOMER motif enrichment
  * RNAseq_07 - Quantifying transcript abundance and differential expression with Kallisto and Sleuth
  * RNAseq_08 - Gene-set enrichment with CensensusPathDB and limma
* data/ - _contains any data used in this project_
  * 01_raw/
  * 02_clean/
  * 03_augmented/
* results/ - _contains results files_
  * figures/
  * tables/