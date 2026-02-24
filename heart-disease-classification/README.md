# Heart Disease Classification (Random Forest)

## Overview
This project builds a machine learning model to predict the presence of heart disease using clinical patient data.

## Dataset
The dataset contains 1025 patient records with 13 medical features, including:
- Age
- Chest pain type
- Cholesterol
- Maximum heart rate
- Number of major vessels
- ST depression (oldpeak)
- And others

The target variable indicates whether heart disease is present (1) or not (0).

## Model
A RandomForestClassifier was trained using an 80/20 stratified train-test split.

## Results
- Test Accuracy: ~100%
- Cross-validation accuracy: ~99.7%
- Most important features:
    - Chest pain type (cp)
    - Maximum heart rate (thalach)
    - Number of vessels (ca)
    - ST depression (oldpeak)

## Interpretation
The model places the highest importance on stress-related and structural heart indicators, suggesting it learns medically meaningful patterns from the dataset.