# Salary-Predictor

This repository contains a simple Linear Regression model designed to predict salaries based on a single variable (e.g., years of experience). The project demonstrates the effectiveness of linear regression for salary prediction and provides comparisons with other models like Random Forest, Lasso, and Ridge Regression.

**Key Features**

Implements a single-variable Linear Regression model to predict salaries.

Provides comparative analysis of performance metrics, including R² scores, for Linear Regression, Random Forest, Lasso, and Ridge Regression.

Explores data skewness and kurtosis for distribution insights.

Demonstrates model evaluation using R² scores to highlight predictive performance.

**Data Insights**

The dataset exhibits the following characteristics:

Positive Skewness: The data is slightly right-skewed, indicating the presence of higher outlier values.

Negative Kurtosis: The data has lighter tails and is less peaked compared to a normal distribution.

**Model Performances**

Linear Regression (R²): 0.7509

Lasso Regression (R²): 0.7509

Ridge Regression (R²): 0.7509

Random Forest (R²): 0.7539 (slight improvement over other models)


**Future Work**

Feature expansion: Incorporate additional variables for better salary prediction accuracy.

Model optimization: Hyperparameter tuning to improve Random Forest performance.

Experimentation with transformations: Normalize skewed data using log transformations.
