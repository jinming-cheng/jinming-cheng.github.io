---
title: "Unraveling the timeline of gene expression: A pseudotemporal trajectory analysis of single-cell RNA sequencing data"
collection: publications
category: manuscripts
permalink: /publication/2023_Cheng_F1000Res
excerpt: 'This paper demonstrates a workflow of pseudotime course analysis for single-cell RNA data.'
date: 2023-11-10
venue: 'F1000 Research'
paperurl: 'https://f1000research.com/articles/12-684/v2'
citation: 'Cheng, J., Smyth, G. K., and Chen, Y. (2023). &quot;Unraveling the timeline of gene expression: A pseudotemporal trajectory analysis of single-cell RNA sequencing data.&quot; <i>F1000 Research</i>. 12.'
---

In this article, we demonstrated a complete workflow of a pseudo-temporal trajectory analysis of scRNA-seq data. This workflow takes single-cell count matrices as input and leverages the *Seurat* pipeline for standard scRNA-seq analysis, including quality control, normalization, and integration. The *scDblFinder* package is utilized for doublet prediction. Trajectory inference is conducted with *monocle3*, while the *edgeR* QL framework with a pseudo-bulking strategy is applied for pseudo-time course analysis. 