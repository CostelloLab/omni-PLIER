# omni-PLIER

# Overview
This repository contains the necessary scripts to reproduce the figures from A Pathway-Level Information ExtractoR (PLIER) framework to gain mechanistic insights into obesity in Down syndrome.

# Installation 
To download the  necessary scripts, clone this repository with: 
```
git clone https://github.com/CostelloLab/omni-PLIER.git
```

# Dataset: Human Trisome Project (HTP) RNA Sequencing Dataset
Under a study protocol approved by the Colorado Multiple Institutional Review Board (COMIRB
#15-2170), the Crnic Institute enrolled participants as part of the Human Trisome Project (HTP;
www.trisome.org). Demographic data for study participants were derived from participant and
caregiver surveys and the annotation of medical records. Clinical variables relevant to this study
include karyotype, age at visit, sex, and body mass index (BMI).
A detailed description of blood processing and molecular quantification for -omic profiling
performed by the Human Trisome Project is described by Galbraith et al. and Waugh et al.
.
Briefly, PAXgene RNA Tubes (Qiagen) were used to collect blood samples from 304 T21 and 95
D21 individuals. Whole-blood paired-end RNAseq was performed using Illumina NovaSeq 6000
instrument (Novogene). Reads were filtered for low quality, and adapters were trimmed. Reads
were aligned to the human reference genome (assembly GRCh38) using STAR2 and quantified at
the gene level to transcripts per million (TPM).
