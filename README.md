<div align="center">
  <img src="assets/alphaband-banner.svg" alt="Alpha Band Detection and Staging" width="100%">
  <br>
  <p><strong>EEG analysis for alpha-band detection and seizure staging</strong></p>
  <p>
    <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
    <img alt="Jupyter" src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white">
    <img alt="EEG" src="https://img.shields.io/badge/Domain-EEG%20Research-7C3AED?style=for-the-badge">
  </p>
</div>

## About

This repository contains notebook-based workflows for **alpha-band seizure detection** and **seizure staging** from EEG recordings. Each task is organized into preprocessing, model training, inference, and evaluation notebooks, with additional analysis notebooks for explainability and extended results.

## Project layout

| Folder | Contents |
| --- | --- |
| [`Alpha Band Detection/`](./Alpha%20Band%20Detection/) | Notebooks for binary seizure detection, including XAI analysis |
| [`Alpha Band Staging/`](./Alpha%20Band%20Staging/) | Notebooks for seizure-stage classification and extended results |
| [`Results_and_Figures/`](./Results_and_Figures/) | Generated figures and result tables |

### Detection workflow

1. `01_data_preprocessing.ipynb` — prepare EEG data
2. `02_training.ipynb` — train detection models
3. `03_inference.ipynb` — run model inference
4. `04_evaluation.ipynb` — evaluate detection performance
5. `06_XAI_analysis.ipynb` — inspect model explanations

### Staging workflow

1. `01_data_preprocessing.ipynb` — prepare EEG data
2. `02_training.ipynb` — train staging models
3. `03_inference.ipynb` — run model inference
4. `04_evaluation.ipynb` — evaluate staging performance
5. `05_Extended_result.ipynb` — generate extended results

## Getting started

1. Clone or download this repository.
2. Open the notebook for the task you want to run in Jupyter Notebook or JupyterLab.
3. Ensure the required EEG dataset and Python dependencies are available in the locations expected by the notebook.
4. Run the workflow notebooks in order, from preprocessing through evaluation.

> **Data and generated files:** Dataset files, preprocessed data, and generated figures are not tracked by Git. Add the required source data locally before running the workflows.

## Notes

- Notebooks are grouped by task; similarly named notebooks in different folders belong to separate workflows.
- Figures and tables in `Results_and_Figures/` are generated outputs and can be recreated by running the notebooks.

---

<div align="center">
  <sub>Built for reproducible EEG analysis and research.</sub>
</div>
