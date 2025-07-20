# Cosmic Legacy: A Search for Foundational Structure in the CMB

**A research project by Dr. Elena Petrova**

### Overview

This repository documents the search for a 'legacy' embedded within the fabric of the cosmos. It contains the complete codebase for my research into anomalous patterns within the Cosmic Microwave Background (CMB). This project moves beyond standard cosmology, testing the hypothesis that the cosmic 'noise' itself contains a complex, non-random structure—a foundational signal that could predate the universe as we know it.

### Methodology

The approach is divided into three main stages:

1.  **Data Preprocessing:** The raw CMB data, stored in HEALPix format, is cleaned, normalized, and divided into patches for analysis. This step is crucial for feeding cosmological data into standard deep learning pipelines.
2.  **Anomaly Detection:** A Variational Autoencoder (VAE) is trained on a vast number of simulated CMB patches that conform to the standard cosmological model. The trained model is then used to identify real CMB patches that it fails to reconstruct accurately—these are flagged as anomalies.
3.  **Statistical Analysis & Visualization:** The flagged anomalies are analyzed for statistical significance. We will investigate their distribution across the sky to determine if they correlate with known cosmic structures or form new, unrecognized patterns.

### Data Source

The primary data used in this research is the **Planck 2018 Legacy Data Release**, accessible via the [Planck Legacy Archive](https://pla.esac.esa.int/pla/). Scripts for downloading and preprocessing the data are included in the `/src/data` directory.

### Repository Structure

-   **/src**: Contains the core Python source code.
    -   `data_loader.py`: Scripts for fetching and preprocessing CMB maps.
    -   `models.py`: Definitions of the VAE and other neural network architectures.
    -   `train.py`: The main script for training the anomaly detection model.
    -   `evaluate.py`: Scripts for applying the trained model to real data and finding anomalies.
-   **/notebooks**: Jupyter notebooks for exploratory data analysis, visualization, and step-by-step breakdowns of the methodology.
    -   `01_CMB_Data_Exploration.ipynb`: Initial exploration and visualization of Planck data.
    -   `02_VAE_Model_Training.ipynb`: Interactive notebook detailing the model training process.
    -   `03_Anomaly_Analysis.ipynb`: Analysis and visualization of the detected anomalies.
-   **/data**: (Initially empty) Directory for storing downloaded CMB maps and processed data patches.
-   `requirements.txt`: A list of all necessary Python packages.

### Getting Started

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/petrova-cosmo/CosmicLegacy.git](https://github.com/petrova-cosmo/CosmicLegacy.git)
    cd CosmicLegacy
    ```
2.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
3.  **Download data:**
    Follow the instructions in `notebooks/01_CMB_Data_Exploration.ipynb` to download the necessary data from the Planck Legacy Archive.
4.  **Run the analysis:**
    Explore the Jupyter notebooks in the `/notebooks` directory to follow the research from start to finish.

### Citing this Work

If you use the code or methods from this repository in your research, please cite it. (Placeholder for citation format).
