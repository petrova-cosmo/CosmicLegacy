# Cosmic Legacy - Analysis v2.0: Polarization Scan

### Overview

This directory contains the second version of the notebooks used to analyze the Planck 2018 CMB data. The goal of this stage was to incorporate multi-channel polarization data (I, Q, and U) to find more subtle anomalies.

The workflow was intended to be similar to v1, but the model training ultimately failed. This analysis and its failure are documented in the Substack post **["I've Hit a Wall. The Data Refuses to Cooperate."](https://open.substack.com/pub/petrovacosmo/p/ive-hit-a-wall-the-data-refuses)**.

### Notebooks

* **`01_Data_Prep_v2_Multi_Channel.ipynb`**: Sourcing and preparing the three-channel (I, Q, U) patch dataset.
* **`02_Model_Training_v2_Multi_Channel.ipynb`**: The failed attempt to build and train a VAE on the polarization data.

### Result: Training Failure

The VAE model **failed to converge** when trained on the multi-channel polarization data. The reconstruction loss did not decrease, indicating the model was unable to learn the underlying patterns in the data.

This unexpected result is considered a significant finding in itself, suggesting that the data may have properties that resist this type of analysis, a concept Prof. Finch might describe as a "firewall." The notebooks are shared for transparency and to invite community feedback.

## Data & Models

The code in this repository relies on external data files (CMB maps) and trained model weights, which are not stored in Git due to their size.
All necessary files for **v2.0** can be downloaded from the following shared folder:
* **https://drive.google.com/drive/folders/1qNExvYk8vrT0ta_ZpLL_ihZMNy6T5fZL**

Please download the contents and place them in your project's `/data` and `/models_v2` directories accordingly.
