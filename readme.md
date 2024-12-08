# TESLA: Tumor-Educated Spatial Learning Algorithm for Spatial Transcriptomics Analysis

## Overview

This repository contains the implementation of **TESLA** (Tumor-Educated Spatial Learning Algorithm), a novel computational method for analyzing spatial transcriptomics data. TESLA is designed to enhance gene expression patterns, annotate tissue regions, characterize intra-tumor heterogeneity, and detect tertiary lymphoid structures (TLS) in cancer tissues.

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Methodology](#methodology)
- [Results](#results)
- [Contributors](#contributors)
- [Citation](#citation)

  

## Introduction

Spatial transcriptomics is a powerful technology that allows for the measurement of gene expression while preserving spatial information within tissue samples. TESLA leverages this technology to provide deeper insights into tumor microenvironments, particularly focusing on:

- Enhancing gene expression patterns
- Annotating tissue regions
- Characterizing intra-tumor heterogeneity
- Detecting tertiary lymphoid structures (TLS)

## Installation

To set up the TESLA environment, follow these steps:

```bash
cd ./TESLA/TESLA_package/
conda env create -f environment.yml
conda activate tesla2
python3 setup.py build
python3 setup.py install
```

## Note
For the model that should put in the ./result file, please reference to [Jian Hu, et al.](https://drive.google.com/drive/folders/1hC6ldkxmZX0yiCWZR57iMXjWIIm9qUJU?usp=sharing)


## Usage

The main steps for using TESLA are:

1. Import required modules
2. Read in spatial transcriptomics data
3. Perform gene expression enhancement
4. Annotate regions
5. Characterize intra-tumor heterogeneity
6. Detect TLS

For detailed usage instructions, refer to the Jupyter notebook in this repository.

## Methodology

TESLA employs several advanced computational techniques:

- **Gene Expression Enhancement**: Utilizes contour detection and preprocessing steps to improve gene expression signal.
- **Region Annotation**: Applies machine learning algorithms to annotate different tissue regions.
- **Intra-tumor Heterogeneity Analysis**: Uses clustering and dimensionality reduction techniques to characterize tumor heterogeneity.
- **TLS Detection**: Implements a specialized algorithm to identify tertiary lymphoid structures within the tumor microenvironment.

## Results

The TESLA algorithm has been validated on multiple spatial transcriptomics datasets, demonstrating its ability to:

- Improve the resolution of gene expression patterns
- Accurately annotate different tissue regions within tumor samples
- Provide insights into intra-tumor heterogeneity
- Identify tertiary lymphoid structures with high precision

For detailed results and visualizations, please refer to the associated publication.

## Project Contributors

This project is a collaborative effort by:

- Beilan Lin (2130034021)
- Junxi Li (2130026073)
- Jiecheng Liao (2130026083)
- Yichen Yuan (2130026190)
- Shi He (2130026041)

Under the guidance of instructor Dr. Jiaxin Chen.

## Citation

We are very thankful for the work provided by Jian Hu, et al.

Hu, J., Coleman, K., Zhang, D., Lee, E. B., Kadara, H., Wang, L., & Li, M. (2023). Deciphering tumor ecosystems at super resolution from spatial transcriptomics with TESLA. Cell systems, 14(5), 404-417.
