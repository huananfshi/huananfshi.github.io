---
layout: post
title: "Multi-omics Analysis Workflow for gut microbiome"
author: "Huanan Shi"
categories: bioinformatics
tags: [workflows]
---
# [Multi-omics Analysis Workflow for gut microbiome](https://github.com/huananfshi/microbiome_multiomics_analysis_workflow)
### An example to integrate and analyze 16s and WGS sequences of gut microbiome, and non-targeted metabolomics. Statistical analysis and machine learning models were used for functional prediction and exploration.
**The repository contains all scripts for paper [Restructuring the Gut Microbiota by Intermittent Fasting Lowers Blood Pressure](https://doi.org/10.1161/circresaha.120.318155).** <br />
**Please cite our paper if you use my workflow.** <br />
**(See [other repository](https://github.com/huananfshi/16s_microbiome_analysis_workflow) for analysis of microbiome 16s rRNA sequencing)** <br />
**If you are reading this, I assume that you have some basic understanding of using Python, R, and Shell. If you want to know more about packages I used here, please go to their websites. Some codes can be simplified. There are several repeated steps that can be combined if run this workflow in order.** <br />
**Modify these code to best suit for your needs.** <br />

1. required package:
  * python: `Numpy`, `scipy`, `seaborn`, `pandas`, `statsmodels`, `matplotlib`, and `scikit-learn`  
  * R: `vegan`, `DADA2`, `biomformat`,`ComplexHeatmap`, `circlize`, `ggplot2`, `RColorBrewer`, `car`, `mixOmics`, and `WRS2`.
  * Commandline tools: `biobakery_workflow`, `HUMAnN3`, `MetaPhlAn3`, `biom-format`
  * Others: `LEfSe`, `GraphPad Prism 9`
 
 
2. workflows (detailed version coming soon)
3. citations:
  
