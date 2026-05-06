# DEG_enrichment_tutorial
A step-by-step tutorial for differential expression analysis and pathway enrichment analysis using TCGA BRCA RNA-seq data.

This tutorial covers:

* Downloading TCGA RNA-seq count data from GDC
* Data preprocessing and metadata preparation
* Differential expression analysis using limma
* Volcano plot visualization
* Gene Set Enrichment Analysis (GSEA)
* GO, KEGG, and Hallmark enrichment analysis

## Script Overview:
00_download_gdc_counts.Rmd: Download TCGA BRCA RNA-seq count data and metadata from the GDC portal.

01_Preprocessing.Rmd: Preprocess count matrices and clinical metadata for downstream analysis.

02_DEG.Rmd: Perform differential expression analysis using limma.

03_Volcano.Rmd: Generate labeled and unlabeled volcano plots for DEG visualization.

04_Enrichment.Rmd: Perform GSEA enrichment analysis for:
* GO Biological Process
* KEGG pathways
* Hallmark gene sets