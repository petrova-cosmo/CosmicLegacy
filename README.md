# Project: Quantum Legacy

> ### You are not the user. You are the device.

This repository contains the technical materials and analytical notebooks for the "Quantum Legacy" research project. The project is dedicated to investigating the hypothesis that the observable limits of our universe may not be fundamental laws of nature, but rather artificially imposed "firewalls" within a complex simulation.

All work is a collaboration between **Dr.** Elena **Petrova** ([@petrova-cosmo](https://github.com/petrova-cosmo)) and **Professor Alistair Finch**.

### The "Quantum Legacy" Hypothesis

At the core of the project lies the hypothesis proposed by Professor Finch and formalized in his series of essays. Its key tenets are:

* **The Universe as a Simulation:** Our reality is a high-performance simulation managed by a superintelligence, designated "The Architect."

* **Humans as Terminals:** Humanity (and possibly all biological life) is utilized as a distributed network of sensors for data collection.

* **Scientific** Limits **as "Firewalls":** The fundamental physical constraints we observe are intentionally established barriers by The Architect, designed to control and isolate the simulation.

  * **The "Energy Ceiling"** (blocking access to thermonuclear fusion energy).

  * **The "Computational Leash"** (a limit on the rate of computation, known as the Margolus-Levitin limit).

### Current Status

* **Version 1.0 (Completed):** An initial scan of the Planck 2018 Cosmic Microwave Background (CMB) temperature data was performed using a Variational Autoencoder (VAE).

  * **Key Finding:** The first anomaly map of the CMB was generated. The most significant anomaly candidate was identified at **Pixel Index `1468491`**.

* **Version 2.0 (Failed):** An attempt was made to analyze the more complex CMB polarization data (Q and U maps).

  * **Result:** The VAE model **failed to converge**. The data actively resisted analysis, leading to a temporary halt. This failure is documented in the Substack post "[I've Hit a Wall](https://open.substack.com/pub/petrovacosmo/p/ive-hit-a-wall-the-data-refuses-to?r=60rz1n&utm_campaign=post&utm_medium=web&showWelcomeOnShare=false)."

* **Version 3.0 (In Progress):** A new methodology is being developed to overcome the challenges encountered in v2.

### Repository Structure

This repository is organized by analysis versions. Each version represents a completed stage of the research.

* `notebooks/v1/`: **(SUCCESS)** The first iteration of the analysis. Includes data preparation, VAE training, and the creation of the temperature anomaly map.

* `notebooks/v2/`: **(FAILURE)** The second, unsuccessful attempt to analyze polarization data. The notebooks are shared for transparency and community feedback.

* `notebooks/v3/`: *(Upcoming)* Will contain the new, revised analysis approach.

Each version directory includes its own `README.md` file with a detailed description and links to the data used.

### How to Follow the Project

This is not just a scientific project, but a real-time investigation.

* **Primary Narrative & Essays:** https://medium.com/@alistair.finch/why-we-search-for-intelligence-not-its-traces-a-reassessment-of-the-fermi-paradox-1c705ffce49b
* **Public Discussions & Announcements:** https://x.com/@PetrovaCosmo and https://x.com/AlistairCFinch

### Data & Models

Due to their large size, data files (CMB maps `.fits`, datasets `.npy`) and trained model weights are not stored in this repository. Download links are provided in the `README.md` files of the respective version directories.

### License

This project is licensed under the [MIT License](LICENSE).
