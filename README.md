<!-- PROJECT HEADING -->
<br />

<h1 align="center">EndoGen</h1>
<p align="center">
Pre-train REBEL model on medical text
<br />
<br />

</p>

## Introduction

This repository creates a pre-training REBEL model (joint entity and relation extraction) on medical text dataset with entities and relations built from UMLS. 


### Problem Statement

Although REBEL model achieves high performance in many relation datasets, the performance of REBEL on medical dataset can still be improved by pretrain the model on medical specific texts. In this project, we aim to train med_REBEL, REBEL model with medical specific knowledge and provide a better solution for medical NLP entity and relation extractions.

### Our Solution

We create MIMIC relation dataset with entities and relations built from UMLS and further selected with NLI model. 

### Applications

By addressing these specific needs, the med-REBEL model serves as a base model for:

- extract entities and relations defined in UMLS 
- fine-tune for downstream extraction applications
  


## Contact
For bug reports and feature requests please raise a GitHub issue on this repository or contact Leo Zhang (leo.xinyue.zhang@kcl.ac.uk) or Tao Wang (tao.wang@kcl.ac.uk)

