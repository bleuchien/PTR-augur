# PTR-Augur

## TL;DR

Predicting the Protein-to-mRNA ratio (PTR) in 29 human tissues from RNA sequence plus some annotation information using deep neural networks.

## Longer Version

The PTR is different per transcribed gene and per tissue. To find the ratio costly measurements of RNA and protein abundance need to be done in a laboratory. Instead of in-vitro work there have been many attempts to predict the PTR with different methods and varying success. Almost all those attempts still relied on expensive measurements as input for the prediction. The approach relies only on the mRNA sequence (from Ensembl) and annotation data from (GenCode). 

## What's Where?

The **data** directory contains the output of the pre-processing Jupyter notebooks.
The **notebooks** directory contains all the Jupyter notebooks for this project.
