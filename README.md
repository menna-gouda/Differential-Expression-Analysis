# DESeq2 Analysis for Differential Expression in Lactation and Location Factors

# About
This project applies the DESeq2 model for differential expression analysis, considering two factors: lactation and location, to the provided dataset. The analysis compares normalized counts between lactating, non-lactating, and control groups for the top 6 genes. DESeq2 assumes a negative binomial distribution for count data.

# Installation
As this project involves analysis using the DESeq2 model, ensure you have R and the necessary R packages installed, including DESeq2. You can install R packages using the install.packages() function.

# Usage
This project facilitates the comparison of gene expression levels across different lactation and location groups using DESeq2 analysis. It provides insights into the differential expression patterns and statistical significance of genes under different conditions.

# Potential Applications
1. Biological research in lactation biology and animal science
2. Understanding gene expression regulation in mammalian systems
3. Identification of candidate genes associated with lactation and location factors
4. Comparative genomics and transcriptomics studies in livestock species

# Features
1. Application of DESeq2 model for differential expression analysis
2. Consideration of two factors: lactation and location
3. Visualization of normalized counts and differential expression results
4. Removal of zero-count genes to increase statistical power
5. Assessment of false discovery rate (FDR) adjusted p-values for significance testing

# Results
The analysis results are presented through visualizations, including graphs showing the relationship between dispersion and mean of normalized counts, and heatmaps depicting overall differential expression patterns across lactation and location groups. Interpretation of significant gene expression changes and implications for lactation and location biology are discussed.
