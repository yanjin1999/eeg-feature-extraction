# EEG Resting-State Analysis Pipeline

This repository demonstrates a basic pipeline for resting-state EEG analysis using Python and MNE.

## Project Overview

The workflow includes:

1. EEG data loading and preprocessing  
2. Artifact inspection and signal cleaning  
3. Epoch segmentation  
4. Power spectral density (PSD) analysis  
5. Feature extraction for machine learning

## Notebooks

### 01_eeg_preprocessing.ipynb
EEG preprocessing pipeline including:
- Raw EEG loading
- Signal filtering
- Artifact inspection
- Epoch segmentation

### 02_eeg_feature_extraction.ipynb
Feature extraction from EEG epochs including:
- Power spectral density calculation
- Frequency band power extraction
- Log transformation of features

## Tools

- Python
- MNE-Python
- NumPy
- Pandas
- Matplotlib

## Notes

The dataset used in this project is not included due to size and privacy considerations.  
The notebooks display the full analysis pipeline and results.
