# bank-customer-churn-prediction

This repository contains a Jupyter Notebook dedicated to predicting customer churn for a bank using machine learning techniques. The project explores various classification models and optimization strategies to achieve the best predictive performance.

## Overview

The primary goal of this project was to predict whether a customer is likely to churn based on their demographic and transactional data. Multiple machine learning models and feature selection techniques were implemented to enhance the model's performance.

## Models Attempted

1. **Logistic Regression**  
   A baseline model for binary classification.
   
2. **Decision Tree**  
   A tree-based model to capture non-linear patterns.

3. **Random Forest**  
   An ensemble method using multiple decision trees.

4. **GradientBoostingClassifier**  
   A powerful boosting algorithm for enhanced accuracy.

5. **HistGradientBoosting**  
   An advanced variant of Gradient Boosting optimized for large datasets.

6. **AdaBoostClassifier**  
   A boosting method to improve weak classifiers.

7. **Voting Classifier**  
   A combination of multiple models to leverage their strengths.

## Techniques Attempted

- **Grid Search**  
   Performed hyperparameter tuning to optimize model performance.
   
- **Feature Selection**  
   Identified and retained the most important features to improve accuracy and reduce overfitting.

## Best Model

The best-performing model was **Gradient Boosting** with Grid Search and Feature Selector. This model demonstrated superior predictive accuracy and reliability in identifying churn-prone customers.

## Features of the Project

- Comprehensive evaluation of multiple classification algorithms.
- Implementation of hyperparameter tuning using Grid Search.
- Feature selection to enhance model interpretability and performance.
- Detailed comparison of models with metrics such as accuracy, precision, recall, and F1-score.
