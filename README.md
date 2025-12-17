# Medical Risk Prediction with Explainable XGBoost

## Overview
This project builds a medical risk prediction model to identify the likelihood
of diabetes based on patient clinical measurements. Model predictions are
interpreted using SHAP for transparency and explainability.

## Dataset
Pima Indians Diabetes Dataset containing diagnostic health measurements.

Target variable:
- 0 → No diabetes
- 1 → Diabetes

## Methodology
- Gradient boosting (XGBoost)
- Probabilistic binary classification
- ROC-AUC based evaluation
- SHAP for global and local explainability

## Explainability
SHAP values are used to:
- Identify globally important risk factors
- Explain individual patient predictions
- Improve trust in medical AI decisions

## Technologies
- Python
- XGBoost
- scikit-learn
- SHAP
- Matplotlib
