## UO Molecular Anthropology Group // Genomics Training Module

This module is an end-to-end differential expression analysis (DGE) workflow which can be applied to a variety of biological questions using RNA-seq data. The module requires a working knowledge of R and will utilize the R integrated environment RStudio.

## Learning Objectives

- Process raw RNA-seq data to prepare for DE analysis
- Perform QC on count data using Principal Component Analysis (PCA) and heirarchical clustering
- Perform DE analysis using DESeq2
- Visualizing expression patterns of differentially expressed genes

## Contents

| Submodules            | 
|:------------------------|
|[Introduction to Differential Expression Analysis Part 1](Submodule/Intro_DE_pt1.md)
|[Introduction to Differential Expression Analysis Part 2](Submodule/Intro_DE_pt2.md)
|[RNA-seq QC using principal component analysis (PCA) and heirarchical clustering](Submodule/QC_sample_clustering.md)
|[Perform Differential Expression Analysis with DESeq2](Submodule/Perform_DE_analysis.md)

### Installation Requirements
Download the most recent versions of R and RStudio for your laptop:

 - [R](http://lib.stat.cmu.edu/R/CRAN/) 
 - [RStudio](https://www.rstudio.com/products/rstudio/download/#download)
 
Install the required R packages by running the following code in RStudio:

```r
source("http://bioconductor.org/biocLite.R") 
biocLite(c("RColorBrewer", "pheatmap", "DESeq2"))
```

Load the libraries to make sure the packages installed properly:

```r
library(DESeq2)
library(ggplot2)
library(RColorBrewer)
library(pheatmap)
```
