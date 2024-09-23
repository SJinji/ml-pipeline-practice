# Machine Learning Pipeline Practice

This repository contains a machine learning pipeline practice script that demonstrates the use of various preprocessing, dimensionality reduction, and classification techniques on a dataset. The pipeline includes data preprocessing, feature scaling, PCA, and model training with hyperparameter optimization using `GridSearchCV`.

## Project Overview

The purpose of this project is to create a reusable and efficient machine learning pipeline that can be easily adapted for different datasets and classification tasks. The pipeline is built using Python and the scikit-learn library, and it incorporates the following steps:

1. **Data Preprocessing**:
    - Handle missing values.
    - Encode categorical variables.
    - Scale numerical features.

2. **Dimensionality Reduction**:
    - Apply Principal Component Analysis (PCA) to reduce the dimensionality of the data.

3. **Classification**:
    - Train a logistic regression classifier with hyperparameter optimization using `GridSearchCV`.

## Dataset

The dataset used in this project is the **bone marrow dataset** stored in the `bone-marrow.arff` file. The target variable is `survival_status`, and various features related to bone marrow transplantation are used as input.


## Expected Output:

   The script will preprocess the data, fit a logistic regression model, optimize hyperparameters using `GridSearchCV`, and print the following information:
   - Accuracy of the initial pipeline on the test set.
   - The best model found using grid search.
   - The hyperparameters of the best model.
   - The number of PCA components selected.
   - Final accuracy of the best model on the test set.

