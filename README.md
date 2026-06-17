# Rice-Immune-Gene-Prioritization-PU-Learning
# Rice Immune Gene Prioritization Using Positive-Unlabeled Learning

A machine learning framework for identifying novel immune-associated genes in Oryza sativa under chitin-triggered immunity.

## Overview

Traditional differential expression analysis identifies genes that change significantly after pathogen stimulation, but may miss regulatory genes with subtle expression patterns.

This project combines:

- RNA-seq analysis
- Differential gene expression
- Feature engineering
- Positive-Unlabeled Learning
- Co-expression network analysis

to prioritize novel immune-related genes in rice.

## Pipeline

RNA-seq
↓
Quality Control
↓
Alignment
↓
FeatureCounts
↓
DESeq2
↓
Feature Engineering
↓
PU Learning
↓
Gene Prioritization
↓
Co-expression Network Validation

## Key Results

- 394 immune-responsive DEGs identified
- Genome-wide feature matrix generated
- PU-learning model trained on immune genes
- Novel non-DEG immune candidates prioritized
- Network-based validation performed
