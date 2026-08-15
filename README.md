# Data Science Project-2 Fraud Detection Pipeline Imbalanced data sampling, EDA, Pipelining And Multiple Model Trained 

This project focuses on building a supervised machine learning pipeline for detecting suspicious/fraudulent transactions using the dataset prepared during Project 1.

## Objectives

- Create a `FraudTransaction` target feature using patterns from multiple transaction attributes
- Analyze and handle class imbalance
- Apply different imbalance-handling techniques
- Build preprocessing and transformation pipelines
- Train and compare multiple classification models
- Evaluate models using Precision, Recall and Confusion Matrix

## Key Work Performed

### 1. Fraud Feature Engineering
Created the `FraudTransaction` target based on multiple transaction-related factors to identify suspicious transactions.

### 2. Handling Imbalanced Data
Experimented with:
- SMOTE Oversampling
- Undersampling
- Class Weights
- Ensemble-based approaches

Visualized class distributions before and after balancing.

### 3. Preprocessing Pipeline
Implemented preprocessing pipelines for:
- Numerical features
- Categorical features
- Feature transformation
- Data preparation

### 4. Model Training
Trained and compared multiple classification models using Scikit-learn.

### 5. Model Evaluation
Evaluated model performance using:
- Confusion Matrix
- Precision
- Recall
- ROC-AUC

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn
- Jupyter Notebook

## Project Workflow

```text
Project 1 Cleaned Dataset
        ↓
FraudTransaction Feature
        ↓
Class Imbalance Analysis
        ↓
SMOTE / Undersampling / Class Weights
        ↓
Preprocessing Pipeline
        ↓
Model Training
        ↓
Model Comparison
        ↓
Confusion Matrix
        ↓
Precision / Recall / ROC-AUC
