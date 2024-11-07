---
title: "Augmenting bacterial similarity measures using a graph-based genome representation"
collection: publications
permalink: /publication/2024
excerpt: 'Relationships between bacterial taxa are traditionally defined using 16S rRNA nucleotide similarity or average nucleotide identity. Improvements in sequencing technology provide additional pairwise information on genome sequences, which may provide valuable information on genomic relationships. Mapping orthologous gene locations between genome pairs, known as synteny, is typically implemented in the discovery of new species and has not been systematically applied to bacterial genomes. Using a data set of 378 bacterial genomes, we developed and tested a new measure of synteny similarity between a pair of genomes, which was scaled onto 16S rRNA distance using covariance matrices. Based on the input gene functions used (i.e., core, antibiotic resistance, and virulence), we observed varying topological arrangements of bacterial relationship networks by applying (i) complete linkage hierarchical clustering and (ii) K-nearest neighbor graph structures to synteny-scaled 16S data. Our metric improved clustering quality comparatively to state-of-the-art average nucleotide identity metrics while preserving clustering assignments for the highest similarity relationships. Our findings indicate that syntenic relationships provide more granular and interpretable relationships for within-genera taxa compared to pairwise similarity measures, particularly in functional contexts.'
date: 2024-06-28
venue: 'ASM Journals: mSystems'
paperurl: 'https://journals.asm.org/doi/full/10.1128/msystems.00497-24'
citation: 'Ramanan V, Sarkar IN. 2024. Augmenting bacterial similarity measures using a graph-based genome representation. mSystems 9:e00497-24.
https://doi.org/10.1128/msystems.00497-24'
---
Genome relationships amongst bacteria are commonly performed using 16S rRNA comparisons or whole genome comparisons. A motivation of interest in this common protocol was how to consider orthologous sections of the genomes that may have moved around in dynamic circular bacterial genomes.This method is an exploration of taking functional regions of genomes and using them to calculate a distance metric, using a linear genome representation and a geometric distance measure instead of a nucleotide based measure. 

[Download paper here](http://vivekramanan.github.io/files/VR-mSystems-Paper.pdf)

Recommended citation: Ramanan V, Sarkar IN. 2024. Augmenting bacterial similarity measures using a graph-based genome representation. mSystems 9:e00497-24. https://doi.org/10.1128/msystems.00497-24
