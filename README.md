# Diabetes Health Indicators Classification
This project aims to analyze and classify health indicators related to diabetes. Using various machine learning techniques, the project explores data, handles imbalanced classes, and evaluates multiple models to predict diabetes presence.

## Project Overview
The primary goal of this project is to classify individuals based on health indicators to determine if they have diabetes. The project includes data preprocessing, exploratory data analysis, feature selection, handling imbalanced data, and model evaluation.

## Dataset
The dataset used in this project is diabetes_health_indicators.csv, which contains various health metrics and a target variable indicating the presence of diabetes.

## Exploratory Data Analysis
* Load and inspect the dataset
* Basic statistics and data information
* Visualization of data distributions and correlations
* Handling duplicate data
* Feature Selection
* Feature selection is done using the Chi-Squared test to identify features with the most significant impact on the target variable.

## Handling Imbalanced Classes
To address the imbalance in the target variable, we use:

* SMOTE (Synthetic Minority Over-sampling Technique)
* NearMiss under-sampling
  
## Modeling and Evaluation
We employ various machine learning models, including:
* Decision Tree
* XGBoost
* Stacking Classifier (combining Decision Tree and XGBoost)

The models are evaluated using:
* Cross-validation scores
* Confusion matrix
* ROC and Precision-Recall curves
* Feature importance analysis
## Installation
To run this project, ensure you have the following dependencies installed:
`pip install numpy pandas matplotlib seaborn scikit-learn imbalanced-learn xgboost`
