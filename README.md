# This project uses the California Housing dataset to compare the performance of methods like Linear, Ridge, and Lasso Regression, and variable selection.

## Project Overview
This project was done during the course of Statistics: Linear Models at Télécom Paris. It explores methods such as Linear Regression, forward variable selection, hypothesis tests for regression coefficients, ridge regression, Lasso, Elastic Net, Principal Component Analysis (PCA), and Principal Component Regression (PCR).

## Methods Covered

1. **Forward Variable Selection Based on Hypothesis Tests for Regression Coefficients**:
    - This method starts from an empty set of variables \( S \) and iteratively selects variables that are relevant for predicting the target variable \( y \). 
    - At each iteration, one variable is added to the set \( S \) based on its significance.
    - The process continues until a predefined halting condition is met.

2. **Test of No Effect**:
    - Hypothesis testing is used to determine if a variable has no effect on the target variable.
    - This involves statistical tests to check the significance of regression coefficients.

3. **Ridge Regression, Lasso, and Elastic Net**:
    - **Ridge Regression**: Adds a penalty on the size of coefficients to prevent overfitting.
    - **Lasso**: Adds a penalty that can shrink some coefficients to zero, effectively performing variable selection.
    - **Elastic Net**: Combines penalties of both Ridge and Lasso to balance between variable selection and coefficient shrinkage.

4. **Principal Component Analysis (PCA)**:
    - PCA is used to reduce the dimensionality of the data by transforming it into a set of linearly uncorrelated components.
    - It helps in identifying the directions (principal components) that maximize the variance in the data.

5. **Principal Component Regression (PCR)**:
    - PCR involves performing PCA on the predictor variables and then using the principal components as inputs to a linear regression model.
    - This method helps in dealing with multicollinearity and reducing the complexity of the model.

## Dependencies
- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Author
Tarcisio da Silva Bueno