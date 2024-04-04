# 20.440 Project

Group Members: Nickeisha Cuthbert, Emma Finburgh

## Overview
Project Title: Evaluating the Correlation between Stress and Age in the Mouse Brain at the Single Cell Transcriptomic Cell

This repository contains code and data sets necessary to reproduce the figure in the figure folder titled, "Stress_age_umap_plot.png". Based on the previously known correlated effects of aging and stress on the brain, this preliminary analysis (processing, integration, and dimensional reduction) was done to combine two data sets and cluster cells based on similar transcriptional profiles (in the UMAP visualization). The code was generated in the R language (RStudio) for analysis of single cell RNA seq data originating from two different data sets, where the stress data (Brivio, et al) was processed similarly to the age data provided by Ximerakis, et al and then both data sets were combined and clustered.

## Data
The data sets used in this study were generated from separate studies. Ximerakis et al. analyzed and produced a “Single-cell transcriptomic profiling of the aging mouse brain”. Brivio, et al. produced 10X raw sequencing data to look at transcriptional signatures of stress exposure in the mouse hypothalamus. 


## Folder Structure
Code: This folder contains the R code used to analyze the scRNA seq data and generate the figure in 	the figure folder.

Data: This folder contains the citations and links to the two data sets used in this study

Figure: This folder contains the figure that was generated where UMAP dimension 1 vs UMAP dimension 2 is plotted with 42 clusters 
        visualized based on similar transcriptional profiles.

## Installation
Running the included code requires setting up a directory to save the code as well as the .rds files produced throughout the code, and the most recent R software (R language, RStudio) and mainly the Seurat v5 package that is used for analysis and exploration of sc RNA seq data. The code in the 'Code' folder and the data sets from the links in the 'Data' folder can be downloaded, afterwhich the code can be ran in RStudio (or any R language processing environment). Importantly, the directory pathway in the code should be updated to match the users' personal directory set up [update setwd()]. The code will run after this for dimensional reduction and to generate the figure included.

## References:
Ximerakis, M., et al. Single-cell transcriptomic profiling of the aging mouse brain. Nat. Neurosci. 22, 1696–1708 (2019).
Data set: https://portals.broadinstitute.org/single_cell/study/aging-mouse-brain

Brivio, E., et al. Sex shapes cell-type-specific transcriptional signatures of stress exposure in the mouse hypothalamus. Cell reports vol. 42,8 (2023).
Data set: https://male-female-stress.shinyapps.io/shinyapp/
