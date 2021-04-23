# single-cell-analysis
A data analysis pipeline that accepts as input a single-cell synthetic dataset 

## Introduction

For this unsupervised learning assignment five single-cell synthetic datasets were provided. Each dataset provides the gene expression profiles (200 Genes) of 200 cells. The goal was to develop a data analysis pipeline that accepts as input a dataset and implements the following analysis stages in a pipeline:  

- Dimensionality reduction:
  - PCA
  - TSNE
  - UMAP
- Clustering (for each dimensionality reduction technique)
  - Gaussian Mixture Modeling with BIC (Bayesian information criterion)
- Visualization of the results

## Prerequisites - Notes

- The code was developed on a Google Colab notebook(Pipeline.ipynb). Feel free to open it
using that or Jupyter Notebook as well

- The following packages were used to apply dimensionality reduction:
  - PCA: sklearn.decomposition.PCA
  - TSNE: sklearn.manifold.TSNE
  - UMAP: umap-learn
- For clustering (Gaussian Mixture Modelling), sklearn.mixture.GaussianMixture was
used
- Place the datasets or ensure that they are in the same directory as the notebook file
