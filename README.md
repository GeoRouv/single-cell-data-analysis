# single-cell-analysis
A data analysis pipeline that accepts as input a single-cell synthetic dataset 

## Introduction

For this unsupervised learning assignment fiveve single-cell synthetic datasets were provided. Each dataset provides the gene expression profiles (200 Genes) of 200 cells. The goal was to develop a data analysis pipeline that accepts as input a dataset and implements the following analysis stages in a pipeline:  

- Dimensionality reduction:
  - PCA
  - TSNE
  - UMAP
- Clustering (for each dimensionality reduction technique)
  - Gaussian Mixture Modeling with BIC (Bayesian information criterion)
- Visualization of the results
