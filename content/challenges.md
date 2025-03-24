---
title: Hackathon Challenges – Single Cell Multiome Data Analysis
nav: Challenges
---

Outlined below are some general ideas around the theme of analyzing single-cell multimodal data that can be tackled during the hackathon. **Please feel free to generate your own ideas as well!**


## Visualization of scMultiomics

<ins>Best Methods/Practices for Visualizing Different Modalities</ins>

- Visualization techniques for unpaired data (e.g., using MultiVI to align and merge latent spaces)
  - Coverage track (ATAC) + violin (GEX) is used for paired data, are there visualizations for unpaired?
- Dimensionality reduction techniques for visualizing high-dimensional data (e.g., UMAP, t-SNE)

<ins>Challenges in Visualizing Unpaired Data</ins>

- Creating visual representations that highlight correlations between different modalities

## Inferring Gene Expression from Chromatin Accessibility

<ins>Predictive Modeling</ins>

- Using machine learning models to predict true gene expression from chromatin accessibility data
- Developing interpretable models that prioritize transcription factors involved in gene regulation

<ins>Enhancer-Promoter Interactions</ins>

- Benchmarking methods to infer gene regulatory networks from single-cell multiome data (e.g., LINGER)

## Integration of Unpaired Single Cell Multiome Data

- Best practices for integrating unpaired single cell multiome data
- Benchmarking existing integration methods to evaluate their performance (e.g. GLUE, LIGER, MinNet)

