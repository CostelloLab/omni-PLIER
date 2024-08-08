# omni-PLIER
A Pathway-Level Information ExtractoR (PLIER) framework to gain mechanistic insights into obesity in Down syndrome
# Overview
Down syndrome (DS), caused by the triplication of chromosome 21 (T21), is a prevalent genetic
disorder with a higher incidence of obesity. Traditional approaches have struggled to differentiate
T21-specific molecular dysregulation from general obesity-related processes. This study introduces
the omni-PLIER framework, combining the Pathway-Level Information ExtractoR (PLIER) with
the omnigenic model, to uncover molecular mechanisms underlying obesity in DS. The PLIER
framework aligns gene expression data with biological pathways, facilitating the identification of
relevant molecular patterns. Using RNA sequencing data from the Human Trisome Project,
omni-PLIER identified latent variables (LVs) significantly associated with both T21 and body mass
index (BMI). Elastic net regression and causal mediation analysis revealed LVs mediating the
effect of karyotype on BMI. Notably, LVs involving glutathione peroxidase-1 (GPX1) and MCL1
apoptosis regulator, BCL2 family member emerged as crucial mediators. These findings provide
insights into the molecular interplay between DS and obesity. The omni-PLIER model offers a
robust methodological advancement for dissecting complex genetic disorders, with implications for
understanding obesity-related processes in both DS and the general population.

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
