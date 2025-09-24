# β-cell Transcriptome Profiling in Type 2 Diabetes

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Build Status](https://github.com/YOURUSER/beta-cell-transcriptome-T2D/actions/workflows/ci.yml/badge.svg)](https://github.com/YOURUSER/beta-cell-transcriptome-T2D/actions)

Reproducible pipeline for **single-cell RNA-seq analysis of pancreatic β-cells** from healthy and Type 2 Diabetes (T2D) donors.  
This project replicates and extends the workflow from [Segerstolpe et al_., *Cell Metabolism* 2016](https://doi.org/10.1016/j.cmet.2016.08.020), using **Nextflow**, **STAR**, and **DESeq2** to profile gene expression changes and β-cell heterogeneity.

---

## 🚀 Motivation
- Type 2 Diabetes affects 1 in 9 individuals worldwide (IDF 2025).  
- β-cells in islets of Langerhans are central to insulin secretion and glucose homeostasis.  
- Bulk RNA-seq misses heterogeneity; **single-cell RNA-seq** resolves subpopulations and disease-related signatures.  

---

## 🎯 Objectives
- Build a reproducible scRNA-seq pipeline (QC → alignment → quantification → DE analysis).  
- Compare transcriptomes of healthy vs T2D β-cells.  
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

