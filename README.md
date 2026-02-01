# Experimental Data for Modular Application Placement Strategy in Cloud Continuum

## Project Overview
This repository contains the dataset and analysis notebooks for research conducted during a Master's degree focused on optimizing application placement in Cloud Continuum environments. The data was generated using the **iFogSim2** simulation framework to evaluate a proposed modular placement strategy.

## File Descriptions
- `dataset.csv`: The primary dataset containing 4,194 experimental observations across 22 features.
- `01_energyConsumption_predictor_train.ipynb`: Google Colab notebook containing the preprocessing, training, and validation of Machine Learning models used in the study.

## Dataset Details
The dataset consists of **4,194 rows** and **22 columns**. It captures performance metrics and configuration states of Fog nodes and applications.

### Key Columns:
- **Strategy:** The placement algorithm used (e.g., CB-E, MGA, Edgewards).
- **Application:** The simulated application type (e.g., DCNS, VRGame, Translation_Service).
- **Module:** Specific application components (e.g., object_tracker, processingModule).
- **Performance Metrics:** Includes `Delay`, `Network` usage, `EnergyConsumption`, and `DeviceCPUUsage`.
- **Infrastructure Info:** `Device` ID, number of `Instances`, and `Bandwidth` configurations.

## How to Cite
If you use this dataset or code in your research, please cite it as follows:

**APA:**
Reis, G. (2026). Data and Code for Random Forest Energy Consumption Prediction [Data set]. Zenodo. https://doi.org/10.5281/zenodo.18451703

**BibTeX:**
```bibtex
@dataset{reis_2026_zenodo_18451703,
  author       = {Reis, G.},
  title        = {Data and Code for Random Forest Energy Consumption Prediction},
  month        = feb,
  year         = 2026,
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.18451703},
  url          = {[https://doi.org/10.5281/zenodo.18451703](https://doi.org/10.5281/zenodo.18451703)}
}
