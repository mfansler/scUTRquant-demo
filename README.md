## Overview

This repository demonstrates running examples from [the scUTRquant pipeline](https://github.com/Mayrlab/scUTRquant) using GitHub-hosted runners via GitHub Actions. The examples start from raw scRNA-seq data and output 3' UTR isoform counts in the form of Bioconductor `SingleCellExperiment` objects. These demonstration workflows include the entire setup: 

 - installing prerequisites (Mambaforge and Snakemake)
 - downloading resources
 - downloading raw scRNA-seq from 10x Genomics
 - creating the pipeline's Conda environments
 - running the full pipeline

Workflows are found under the [.github/workflows directory](.github/workflows).

## Results

[![OSX - heart_1k_v2](https://github.com/mfansler/scUTRquant-demo/actions/workflows/osx-heart-1k-v2.yaml/badge.svg)](https://github.com/mfansler/scUTRquant-demo/actions/workflows/osx-heart-1k-v2.yaml)

## Acknowledgements

The fact that one can process raw scRNA-seq data to a matrix of 3' UTR isoform counts on minimal resources is made possible by:

 - [**kallisto | bustools** workflow](https://www.kallistobus.tools)
 - [Snakemake](https://snakemake.readthedocs.io/en/stable/)
 - [Mamba](https://mamba.readthedocs.io/en/latest/)
 - [Bioconda](https://bioconda.github.io)
 - [Conda Forge](https://conda-forge.org)

Thanks! ❤️
