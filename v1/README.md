# Cosmic Legacy - Analysis v1.0: Initial Anomaly Scan

### Overview

This directory contains the first version of the notebooks used for the initial analysis of the Planck 2018 CMB data. The workflow is divided into three stages: data preparation, model training, and anomaly detection.

This analysis serves as the proof-of-concept for the methodology proposed in **[https://medium.com/@alistair.finch/why-we-search-for-intelligence-not-its-traces-a-reassessment-of-the-fermi-paradox-1c705ffce49b]**.

### Notebooks

* **`01_CMB_Data_Exploration.ipynb`**: Data sourcing, cleaning, and preparation of the patch dataset.
* **`02_VAE_Model_Training.ipynb`**: Building and training the Variational Autoencoder on "normal" CMB patches.
* **`03_Anomaly_Detection_and_Analysis.ipynb`**: Using the trained VAE to scan the full sky and generate a map of reconstruction errors.

### Key Finding

The initial low-resolution scan successfully identified several anomalous regions. The most significant candidate is **Rank #1 at Pixel Index = 1468491**. Further analysis is required.
