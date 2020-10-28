# Ensemble Feature Selector

## Overview
This project aims to identify redundant variables in order to improve Feature Selection. Relevant variables identification is performed via an Ensemble method based on resampling without replacement. In order to detect redundant variables I perform maximum-relevance minimum-redundancy (MRMR) approaches, plus a novel algorithm which individually swaps each feature set item by an ensemble top-picked variable (rivalry detection).

![Graph containin several coloured connected components](https://github.com/RaulCoroban/EnsembleFeatureSelector_MinorThesis/blob/master/Minor%20Thesis/figures/graphs/main/g95102028.png?raw=true)

## Data
The SNP dataset has been collected on diabetes disease (∼1:64 samples to variables relation). From a machine learning point of view, the method largely reduces the curse of dimensionality. From a medical point of view, the outcome should help to focus only on genetic variables related with the disease, making laboratory validation more affordable. insight.
