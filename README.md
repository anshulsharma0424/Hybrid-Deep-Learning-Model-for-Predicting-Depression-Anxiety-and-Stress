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

### 2. Implementation Steps
#### 2.1. Data Preprocessing
- Convert categorical responses into numerical format.
- Handle missing values and perform normalization.

#### 2.2. Feature Selection
- Use SHAP and RFE to identify the most influential features.

#### 2.3. Class Imbalance Handling
- Apply SMOTE to balance minority and majority classes.

#### 2.4. Model Training
- Train a Deep Neural Network (DNN) to generate embeddings.
- Pass embeddings to an XGBoost classifier for final predictions.

#### 2.5. Hyperparameter Tuning
- Optimize DNN and XGBoost hyperparameters using Grid Search & Bayesian Optimization.

#### 2.6. Model Evaluation
- Evaluate performance using Accuracy, Precision, Recall, and F1-score.

#### 2.7. Explainability with LIME
- Use LIME to explain individual predictions and model behavior.

### 3. Model Architecture

![Final Architecture Diagram](https://github.com/user-attachments/assets/aca1a88f-2c29-41e4-8ff0-0eb49b85b72d)

**Deep Neural Network (DNN):**
- **Input Layer:**  Selected features
- **Hidden Layers:** 3 fully connected layers with ReLU activation
- **Output Layer:** Feature embeddings

**XGBoost Classifier:**
- Takes DNN embeddings as input
- Predicts the class label (Depression, Anxiety, Stress levels)

### Performance Metrics
![image](https://github.com/user-attachments/assets/8e4c487b-5f6f-4176-abb3-3f772854aaf8)

##### Contributor : Anshul Sharma












