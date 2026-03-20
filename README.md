# EEG Alpha State Classification Project

## Project Overview
This project implements a complete EEG signal processing and machine learning pipeline to classify alpha brain states (high vs low alpha activity).

The workflow covers:
- EEG preprocessing (artifact removal, ICA)
- Feature extraction (power spectral density, band power, ratios)
- Machine learning modeling and evaluation

---

## Motivation
Alpha activity (8–12 Hz) is closely related to cognitive states such as relaxation and attention.  
This project aims to build a data-driven pipeline to classify alpha states from EEG signals.

---

## Pipeline

### 1. Preprocessing
- Band-pass filtering
- ICA-based artifact removal (EOG)
- Bad segment rejection

Notebook: `01_preprocessing.ipynb`

---

### 2. Feature Extraction
- Power Spectral Density (PSD)
- Band power (delta, theta, alpha, beta)
- Ratio features (e.g., alpha/theta)

Notebook: `02_feature_extraction.ipynb`

---

### 3. Machine Learning
- Models:
  - Logistic Regression
  - SVM (RBF)
  - Random Forest

- Validation:
  - Time-series cross-validation (to prevent data leakage)

- Metrics:
  - Precision, Recall, F1-score

Notebook: `03_alpha_state_classification.ipynb`

---

## Key Results
- Achieved stable classification performance after removing data leakage
- Demonstrated importance of proper validation in time-series EEG data

---

## Skills Demonstrated
- EEG signal processing (MNE)
- Feature engineering for physiological signals
- Time-series aware machine learning
- Data leakage handling and model validation
- End-to-end pipeline design
