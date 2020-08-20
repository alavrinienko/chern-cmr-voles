# Analysis Notebook
[![DOI](https://zenodo.org/badge/82461239.svg)](https://zenodo.org/badge/latestdoi/82461239)

This repository contains the notebook used to analyse the data in Lavrinienko et al. 2020. The notebook contains commands to process raw read data and reproduce the qiime2 analyses.

This repository provides the main data files, i.e. metadata and dada2 feature-tables, from which the rest of the data can be generated using these commands. The raw sequence data are freely available through Qiita [study ID 12325](https://qiita.ucsd.edu/study/description/12325) or EBI-European Nucleotide Archive: [ERP114357](https://www.ebi.ac.uk/ena/data/view/ERP114357).

## Requirements

qiime2 is required to run most of the commands described below (the 2018.2 qiime2 version was used).
To install qiime2 follow these instructions: https://docs.qiime2.org/2019.1/install/.
To activate the qiime2 conda environment run: source activate qiime2-2019.1 (or the other installed version).

### File explanations

 - qiime2 analysis notebook: chern-cmr-voles-v200419.ipynb
 - Metadata: metadata-malesrt.txt (metadata for wild bank voles from the Chernobyl Exclusion Zone, Ukraine)
 - qiime2 feature-table: malesrt2_table-dada2.qza (the original dada2 feature-table)
 - qiime2 rarefied feature-table: rarefied_table.qza (the 'filtered10', rarefied dada2 feature-table)
 - qiime2 representative sequences: malesrt2_rep-seqs-dada2.qza (the dada2 representative sequences)




Change log: updated code according to the JAE revisions (30/07/2020), see chern-cmr-voles-v300720.ipynb
