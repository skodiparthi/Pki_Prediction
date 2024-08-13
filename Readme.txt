# Multi-Target Machine Learning Model for Predicting pKi Values

This project develops and trains machine learning models to predict pKi values for various molecular targets using RDKit-generated molecular descriptors. The models are trained on different targets within the dataset and saved for future predictions.

# Project Overview

The project consists of two main components:
1. **Model Training (`train_model.py`)**: This script trains machine learning models for each target in the dataset, including Random Forest, XGBoost, and Extra Trees models. Each model is saved with a unique name corresponding to the target it was trained on.
2. **Model Prediction (`predict_ki.py`)**: This script allows you to predict pKi values for a given SMILES string using the trained models.

# Dependencies

- Python 3.x
- RDKit
- NumPy
- Pandas
- Scikit-learn
- XGBoost
- Joblib

Install the required Python packages using:
```bash
pip install rdkit numpy pandas scikit-learn xgboost joblib
