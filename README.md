# 20.440 Project

Group Members: Nickeisha Cuthbert, Emma Finburgh

## Overview
Project Title: Evaluating the Correlation between Stress and Age in the Mouse Brain at the Single Cell Transcriptomic Cell

This repository contains code and data sets necessary to reproduce the figure in the figure folder titled, "Stress_age_umap_plot.png". Based on the previously known correlated effects of aging and stress on the brain, this preliminary analysis was done to combine two data sets and cluster cells based on similar transcriptional profiles. The code was generated in the R language (RStudio) for analysis of single cell RNA seq data originating from two different data sets.

## Data
The data sets used in this study were generated from separate studies. Ximerakis et al. analyzed and produced a “Single-cell transcriptomic profiling of the aging mouse brain”. Brivio, et al. produced raw sequencing data to look at transcriptional signatures of stress exposure in the mouse hypothalamus. Both data sets were useful to investigate 

References:
Ximerakis, M., et al. Single-cell transcriptomic profiling of the aging mouse brain. Nat. Neurosci. 22, 1696–1708 (2019).
Data set: https://portals.broadinstitute.org/single_cell/study/aging-mouse-brain

Brivio, E., et al. Sex shapes cell-type-specific transcriptional signatures of stress exposure in the mouse hypothalamus. Cell reports vol. 42,8 (2023).
Data set: https://male-female-stress.shinyapps.io/shinyapp/

## Folder Structure
Code: This folder contains the R code used to analyze the scRNA seq data and generate the figure in 	the figure folder.
Data: This folder contains the citations and links to the two data sets used in this study
Figure: This folder contains the figure that was generated.

## Installation
Running the included code requires the most recent R software (R language, RStudio). Afterwards, the packages at the beginning of the code can be installed and loaded. The code will run after this to generate the figure included.
