---
title: " Breast Cancer Classification"
excerpt: "This project applies Spectral Clustering techniques for the classification of breast cancer data"
collection: portfolio
---


## Overview
This project applies Spectral Clustering techniques for the classification of breast cancer data. By leveraging the mathematical and algorithmic foundations of spectral clustering, we aim to segment breast cancer datasets into benign and malignant categories with enhanced accuracy and insight into the underlying data structures.

## Key Concepts
- **Spectral Clustering:** An unsupervised machine learning technique used to group similar data points together based on their relationships. Unlike traditional clustering methods, spectral clustering uses the eigenvalues of similarity matrices to reduce dimensions, enabling the identification of clusters in complex datasets.
- **Breast Cancer Classification:** The process of categorizing breast cancer occurrences into benign (non-cancerous) or malignant (cancerous) groups, crucial for determining the appropriate treatment pathways.

## Implementation Details
- `SpectralClustering.ipynb`: Demonstrates the application of spectral clustering using a standard library.
- `SpectralClusteringScratch.ipynb`: Explores the implementation of spectral clustering from scratch, detailing the algorithm's steps and the mathematical principles behind them.
- `implementationCorrectness.ipynb`: Verifies the correctness of the spectral clustering implementation against known benchmarks and datasets.

## Datasets
The project utilizes the Breast Cancer Wisconsin (Diagnostic) dataset, widely used in machine learning research for cancer classification. This dataset includes features derived from digitized images of fine needle aspirates of breast masses, with labels indicating the malignancy of the cancer.

## Getting Started

### Prerequisites
- Python 3.x
- Jupyter Notebook or JupyterLab
- Required Python packages:
  - numpy
  - scipy
  - matplotlib
  - scikit-learn
  - pandas

### Installation
1. Clone the repository to your local machine:
   ```bash
   git clone https://your-repository-url.git
