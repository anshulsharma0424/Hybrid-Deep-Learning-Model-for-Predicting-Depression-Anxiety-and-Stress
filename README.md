# Hybrid Machine Learning Model for Predicting Depression, Anxiety, and Stress

## Overview
This project presents a novel hybrid machine learning approach to predicting Depression, Anxiety, and Stress using deep learning and ensemble techniques. Our implementation integrates Deep Neural Networks (DNN) with XGBoost, stacking classifiers, and feature selection methods such as SHAP and Recursive Feature Elimination (RFE) to improve classification accuracy, finally integrating XAI (Explainable AI) for explaining the predictions of our model.

## Novelty & Key Contributions
- **Hybrid DNN-XGBoost Model:** We combine the feature extraction power of Deep Neural Networks (DNN) with the boosting strength of XGBoost.
- **Feature Selection with SHAP & RFE:** We use SHAP values and Recursive Feature Elimination (RFE) to select the most influential features.
- **Handling Class Imbalance:** Implemented techniques such as oversampling (SMOTE) and weighted loss functions to mitigate imbalance issues in datasets.
- **Explainability with XAI LIME:** Integrated Local Interpretable Model-agnostic Explanations (LIME) to enhance interpretability of predictions.
