# Analysis Notebook

This repository contains the notebook used to analyse the data in Lavrinienko et al. 20XX. The notebook contains commands to process raw read data and reproduce the qiime2 analyses.

This repository provides the main data files, i.e. metadata and dada2 feature-tables, from which the rest of the data can be generated using these commands. The raw sequence data are freely available through Qiita [study ID 12325](https://qiita.ucsd.edu/study/description/12325) or EBI-European Nucleotide Archive.

## Requirements

qiime2 is required to run most of the commands described below (the 2018.2 qiime2 version was used).
To install qiime2 follow these instructions: https://docs.qiime2.org/2019.1/install/.
To activate the qiime2 conda environment run: source activate qiime2-2019.1 (or the other installed version).
