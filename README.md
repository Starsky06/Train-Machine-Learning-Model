# Cardiovascular Risk Prediction

A machine-learning assignment that explores classification of cardiovascular risk categories using structured health-related data.

> **Medical disclaimer:** This project is for educational purposes only. It must not be used for medical diagnosis, treatment, or clinical decision-making.

## Overview

This project applies an end-to-end machine-learning workflow to classify cardiovascular risk into categories such as low, medium, and high.

## Workflow

```mermaid
flowchart LR
    Dataset[dataset.csv] --> EDA[Exploratory Data Analysis]
    EDA --> Clean[Data Cleaning and Preprocessing]
    Clean --> Split[Train/Test Split]
    Split --> Models[Train Multiple ML Models]
    Models --> Evaluate[Evaluate Performance]
    Evaluate --> Compare[Compare Results]
```

## Repository Contents

| File | Description |
|---|---|
| `Training Algorithrm.ipynb` | Main training and evaluation workflow |
| `Training Algorithrm.pdf` | Exported notebook or report |
| `dataset.csv` | Dataset used for model development |

## Learning Objectives

- Perform data preprocessing and exploratory analysis
- Train and compare multiple classification models
- Evaluate model performance with suitable metrics
- Gain hands-on experience with a machine-learning workflow

## How to Run

1. Open `Training Algorithrm.ipynb` in Jupyter Notebook, JupyterLab, or Google Colab.
2. Keep `dataset.csv` in the same working directory.
3. Install the Python libraries used in the notebook.
4. Run the cells from top to bottom.

## Model Evaluation

Replace the placeholders below with the actual output from the notebook before using this project in a presentation.

| Model | Accuracy | Precision | Recall | F1-score |
|---|---:|---:|---:|---:|
| Model 1 | Add result | Add result | Add result | Add result |
| Model 2 | Add result | Add result | Add result | Add result |
| Model 3 | Add result | Add result | Add result | Add result |

## Tech Stack

Python · Jupyter Notebook · pandas · NumPy · scikit-learn · Machine Learning
