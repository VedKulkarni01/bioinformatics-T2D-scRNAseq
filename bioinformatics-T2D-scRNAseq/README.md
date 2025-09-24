# Single-Cell Transcriptomic Profiling of Beta Cells in Human Pancreatic Islets

## 📌 Project Overview
This project reproduces and extends analysis of **single-cell RNA-seq data** 
comparing healthy and Type 2 diabetic pancreatic beta cells.  
It was completed as part of **BINF6310 – Introduction to Computational Methods in Bioinformatics**.

## 👥 Team Members
- Dinesh Sambhaji Pradhan  
- Asmitha Nagajothi Purushotam  
- Vedant Kulkarni  
- Rich Goodier  

## 🎯 Objectives
- Build a reproducible pipeline for scRNA-seq analysis.  
- Compare transcriptomes of beta cells from healthy vs. T2D samples.  
- Identify differentially expressed genes and enriched pathways.  

## 📂 Repository Structure
bioinformatics-T2D-scRNAseq/
├── code/ # documented pipeline (Nextflow, STAR, featureCounts)
├── docs/ # proposal, recreated paper references
├── slides/ # project presentation
├── README.md # project description
└── .gitignore

## 🔬 Methods & Tools
- **QC & Preprocessing:** Cutadapt, FastQC, MultiQC  
- **Alignment & Quantification:** STAR, featureCounts  
- **Analysis:** R (DESeq2, clusterProfiler), Python (pandas, matplotlib), NetworkAnalyst  
- **Pipeline Management:** Nextflow, Conda  

## 📊 Key Results
- Identified downregulation of *INS* and *PDX1* in T2D beta cells.  
- Revealed heterogeneity within beta cells (RBP4+ subpopulations).  
- GSEA showed enrichment of stress and metabolic pathways.  

## 📄 References
- Segerstolpe Å. et al. (2016). *Single-cell transcriptome profiling of human pancreatic islets in health and type 2 diabetes*. Cell Metabolism, 24(4), 593–607. [DOI](https://doi.org/10.1016/j.cmet.2016.08.020)  
- Grenko C. M. et al. (2024). *Single-cell transcriptomic profiling of human pancreatic islets reveals genes responsive to glucose exposure*. Diabetologia, 67(10), 2246–2259. [DOI](https://doi.org/10.1007/s00125-024-06214-4)  
- Raghavan V. et al. (2022). *A simple guide to de novo transcriptome assembly and annotation*. Briefings in Bioinformatics, 23(2), bbab563. [DOI](https://doi.org/10.1093/bib/bbab563)  

---
