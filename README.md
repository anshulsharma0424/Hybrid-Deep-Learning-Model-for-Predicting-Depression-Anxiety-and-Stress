# Hybrid Machine Learning Model for Predicting Depression, Anxiety, and Stress

## Overview
This project presents a novel hybrid machine learning approach to predicting Depression, Anxiety, and Stress using deep learning and ensemble techniques. Our implementation integrates Deep Neural Networks (DNN) with XGBoost, stacking classifiers, and feature selection methods such as SHAP and Recursive Feature Elimination (RFE) to improve classification accuracy, finally integrating XAI (Explainable AI) for explaining the predictions of our model.

## Novelty & Key Contributions
- **Hybrid Model Architecture:** Combines DNN embeddings with XGBoost for classification.
- **Feature Selection:** Implements SHAP and RFE for optimal feature selection.
- **Class Imbalance Handling:** Uses SMOTE (Synthetic Minority Over-sampling Technique) to balance the dataset.
- **Explainability:** Integrates LIME (Local Interpretable Model-Agnostic Explanations) for interpretability.

## Implementation Details

### 1. Dataset
The dataset used is the DASS-42 questionnaire, which consists of 42 self-reported responses categorized into:
- Depression (14 questions)
- Anxiety (14 questions)
- Stress (14 questions)

**Note:** The original responses are on a 1 to 4 scale, converted to a 0 to 3 scale for preprocessing.

