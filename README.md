
# Aim:
   To analyze gene expression data from breast cancer and normal breast tissues, decipher differential expression patterns of breast cancer-associated genes, and generate interactive and informative visualizations using R.

# Packages used:
   This project employed R programming alongside essential packages such as dplyr, tidyverse, ggplot2, and GEOquery to preprocess, analyze, and visualize gene expression data effectively. Various graphical representations including bar plots, density plots, histograms, box plots, and scatter plots were created to elucidate the expression profiles of pivotal genes (e.g., BRCA1, BRCA2, TP53) and their relevance to breast cancer progression and metastasis.

# About the Dataset:
Dataset Overview: Breast cancer ranks among the most prevalent cancers worldwide, impacting millions of women annually. The GSE183947 dataset pertains to breast cancer tissue and encompasses RNA sequencing data derived from 30 pairs of normal and cancerous tissues. The RNA sequencing reads were normalized using Fragments Per Kilobase of transcript per Million mapped reads (FPKM) methodology.

# Note:
(i) RNA Sequencing (RNA-seq) --> measure gene expression, distinct from DNA microarrays.


(ii) FPKM  -->  normalize RNA-seq data. It adjusts read counts by considering both the length of genes and the total number of mapped reads. This helps correct biases that can arise from longer genes being more likely to have multiple reads counted, ensuring more accurate measurements of gene expression levels.



# Summary:
mRNA extracted from both normal and tumor samples is fragmented and converted to cDNA through reverse transcription. Short DNA adapters are attached to the cDNA ends for sequencing platform binding. PCR amplifies these cDNA fragments into a library, sequenced on platforms such as Illumina, PacBio, or Oxford Nanopore. Sequencing platforms then align these cDNA sequences to a reference genome, counting reads per gene or transcript. Raw read counts undergo normalization to adjust for sequencing depth and gene length using methods like FPKM (Fragments Per Kilobase of transcript per Million mapped reads) or TPM. Then, Differential Gene Expression Data Analysis is performed.


