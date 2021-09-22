---
layout: page
title: resources
---

## Docker Images

The following images are ready to run [the notebooks below](#notebooks).  
<details><summary> &#9658; RStudio </summary>
	<p> Image ready to run R 4.1.0, Rstudio, Mixomics 6.16.3, MOFA2 1.3.4, among others.</p>
	<p> Run with <code>docker run ruibenfeitas/rstudio:30_08_2021</code></p></details>

<details><summary> &#9658; Jupyter </summary>
	<p> Image ready to run Python 3.9.6, Jupyter, igraph, scikit-learn, among others.</p>
	<p> Run with <code>docker run ruibenfeitas/jupyter:30_08_2021</code></p></details>

## Notebooks

- [Data pre-processing notebook](../extras/notebooks/session_preprocessing/preprocessing.html) - data overview, cleaning, imputation, anomaly detection, dimensionality reduction, and normalization.

- [Multi-omic network analysis](../extras/notebooks/session_topology/lab.html) - network inference, topology, centrality analysis, and community interrogation in a transcriptomic / metabolomic network.

- [Introduction to Genome-scale metabolic modeling in python](../extras/notebooks/session_gems/lab.html) - brief introduction into flux prediction and analysis of a genome-scale metabolic network.