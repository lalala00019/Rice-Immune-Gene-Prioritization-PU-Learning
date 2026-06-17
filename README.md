
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

## Data Acquisition

RNA-seq datasets obtained from PRJNA1062417

## Quality Control

FastQC
MultiQC

## Trimming

Trimmomatic

## Alignment

HISAT2

## Read Quantification

FeatureCounts

## Differential Expression

DESeq2

## Feature Engineering

Promoter GC
CDS GC
Protein length
W-box motifs
Signal peptide probability
Transmembrane domains

## Machine Learning

Random Forest PU Bagging

## Network Analysis

Pearson correlation
Degree centrality
Candidate prioritization

## Key Results
394 DEGs identified
PU-learning used to rank
~35,000 unlabeled genes
Top candidates validated through
co-expression network topology
Integrated scoring:
PU score + network centrality

- 394 immune-responsive DEGs identified
- Genome-wide feature matrix generated
- PU-learning model trained on immune genes
- Novel 4 non-DEG immune candidates prioritized
- Network-based validation performed
  
## Software

FastQC
MultiQC
Trimmomatic
HISAT2
Samtools
Subread
R
DESeq2
Python

## Environment

Python 3.10
scikit-learn
pandas
numpy
biopython
networkx
