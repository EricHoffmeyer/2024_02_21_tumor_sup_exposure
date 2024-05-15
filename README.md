# 2024_02_21_tumor_sup_exposure

This document will cover the work on a bulk RNAseq dataset.

## 2024_03_07_DESeq_results

This folder contains the results from 2024_03_07_DESeq.qmd, where each condition (separated by cell line) was run against the others, as well as the combined donor treated samples vs the media controls. A GeneTonic object (.Rdata) was also made during each comparison.

## 2024_03_08_Plots_results

Contains plots generated from the DESeq comparisons and .Rdata GeneTonic objects: two heatmaps, a volcano plot, and a summary plot for gene set enrichment.

## 2024_03_15_gprofiler_gene_sets

Contins results from expanded gene set analysis using the gprofiler package.

## 2024_04_03_results

Results from 2024_04_03_drug_antibody_targets where I match the list of shared DE genes against drug/gene list, list of transmembrane proteins (for potential CAR T cell targets), etc.
