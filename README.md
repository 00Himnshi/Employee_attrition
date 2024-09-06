# Employee Attrition Prediction

## Overview
Employee attrition is a major concern for organizations due to the high costs associated with recruiting and training new employees. Predicting employee attrition helps companies take proactive measures to retain valuable staff. This project aims to compare various resampling techniques for handling imbalanced datasets and apply them to multiple supervised learning models for attrition prediction.

## Technologies Used
- Python
- scikit-learn
- imbalanced-learn
- pandas
- IBM HR Analytics dataset

## Project Details
This project involves:
- **Feature Reduction:** Applied PCA and Chi-Square Test to reduce dimensionality before training models.
- **Models Used:** Logistic Regression, Support Vector Machine (SVM), K-Nearest Neighbors (KNN), Decision Trees, Random Forest Classifier, and XGBoost.
- **Resampling Techniques:** Employed techniques such as Random Oversampling, SMOTE, ADASYN, Undersampling, Tomek-Links, ENN, and Hybrid methods to balance the dataset.

## Key Findings
- **Best Performing Model:** Random Forest Classifier.
- **Metrics Achieved:** 
  - Accuracy: 98.18%
  - AUC-ROC Score: 99.99% (with Random Oversampling)
