# Census Income Prediction

## Overview

Developed and evaluated machine learning models to predict whether an individual's annual income exceeds $50,000 using demographic and employment data from the U.S. Census. Compared a traditional machine learning approach (Logistic Regression) with a feedforward Neural Network to determine which model achieved better predictive performance.

## Problem

Financial organizations often need to identify individuals who may qualify for financial assistance or lending programs. This project builds a binary classification model to predict income level based on demographic and employment characteristics.

## Dataset

- U.S. Census Income Dataset
- Binary classification problem
- Target: `income_binary`
    - 0 = Income ≤ $50K
    - 1 = Income > $50K

## Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- TensorFlow / Keras
- Matplotlib
- Seaborn
- Jupyter Notebook

## Machine Learning Pipeline

- Performed exploratory data analysis (EDA)
- Handled missing values
- Applied one-hot encoding to categorical variables
- Selected important features using SelectKBest
- Trained a Logistic Regression classifier
- Tuned hyperparameters using GridSearchCV
- Built and trained a feedforward Neural Network
- Compared model performance using Accuracy and F1 Score

## Results

| Model | Accuracy | F1 Score |
|--------|---------:|---------:|
| Logistic Regression | **83.24%** | **0.595** |
| Neural Network | **83.81%** | **0.623** |

The neural network achieved the highest overall performance, improving both accuracy and F1 score over Logistic Regression.

## Key Takeaways

- Neural networks slightly outperformed traditional machine learning models for this binary classification task.
- Feature engineering and preprocessing significantly improved model performance.
- Evaluated ethical considerations including demographic bias and fairness when using census data for predictive modeling.
