# Machine Learning Project: Interpretable Models and Regression Techniques

## Overview

This project encompasses two major parts: creating interpretable models using decision trees and exploring various regression techniques including LASSO and boosting.

## Part 1: Decision Trees as Interpretable Models

### (a) Data Acquisition

- Download the Acute Inflammations data from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Acute+Inflammations).

### (b) Decision Tree Construction

- Build and plot a decision tree using the entire dataset.

### (c) IF-THEN Rules

- Convert the decision rules from the tree into a set of IF-THEN rules for interpretability.

### (d) Cost-Complexity Pruning

- Apply cost-complexity pruning to derive a minimal decision tree and a simplified set of decision rules.

## Part 2: The LASSO and Boosting for Regression

### (a) Data Preparation

- Download the Communities and Crime data from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Communities+and+Crime).
- Use the first 1495 rows as the training set and the rest as the test set.

### (b) Data Imputation and Feature Selection

- Implement data imputation for missing values and disregard nonpredictive features.

### (c) Correlation Matrix

- Plot a correlation matrix for the dataset features.

### (d) Coefficient of Variation Analysis

- Calculate the Coefficient of Variation (CV) for each feature and select features with the highest CV.

### (e) Visualization and Analysis

- Create scatter plots and box plots for the selected features to analyze their significance.

### (f) Linear Model with Least Squares

- Fit a linear model using least squares on the training set and report the test error.

### (g) Ridge Regression Model

- Implement ridge regression with optimal λ determined by cross-validation and report the test error.

### (h) LASSO Model

- Fit a LASSO model with optimal λ determined by cross-validation.
- Report the test error and selected variables.
- Repeat the process with standardized features and compare the test errors.

### (i) PCR Model

- Fit a Principal Components Regression (PCR) model with the optimal number of components determined by cross-validation.
- Report the test error.

### (j) L1 Penalized Gradient Boosting Tree

- Fit an L1 penalized gradient boosting tree using XGBoost, with α determined by cross-validation.
- Report the findings.

## Objectives

- Develop interpretable models using decision trees.
- Explore and compare different regression techniques including LASSO, ridge regression, PCR, and boosting.
- Evaluate and analyze the performance of each model in terms of error rates and feature selection.
