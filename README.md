# Loan Default
Overview
This repository contains an in-depth analysis of factors influencing loan amounts and approval probabilities using linear regression and logistic regression techniques. The project explores the relationship between borrower characteristics, property values, and loan metrics to provide actionable insights for financial institutions.

**Link:** https://www.kaggle.com/datasets/nikhil1e9/loan-default


# Research Question 1: What factors influence the size of the loan amount?

Key Variables: Income, property value, interest rate spread, debt-to-income ratio, and credit score.
Methodology: Linear regression with transformations (e.g., log scale) to handle non-linearity and heteroscedasticity.


# Research Question 2: What factors predict whether a loan will be approved or rejected?

Key Variables: Loan-to-value ratio, debt-to-income ratio, income (with non-linear terms), interest rate spread, and credit score.
Methodology: Logistic regression to estimate approval probabilities and assess variable significance.
Key Findings
Loan Amount Analysis (Linear Regression):



**Addressed missing values** using KNN imputation for numerical data and most frequent imputation for categorical data.
**Winsorized outliers** and standardized numerical variables for robust modeling.



# Linear Regression:

Adjusted for heteroscedasticity using log transformations.
Ensured multicollinearity and autocorrelation assumptions were met.


# Logistic Regression:

Evaluated model performance using confusion matrices and pseudo R² metrics.
Incorporated non-linear effects through squared terms for income.
Features
Data Preprocessing: Imputation, outlier handling, and standardization.
Advanced Statistical Modeling: Robust standard errors, residual analysis, and VIF checks for multicollinearity.
Visualization: Correlation heatmaps, Q-Q plots, and probability distributions to support insights.


# Tools and Libraries
Python: pandas, numpy, seaborn, matplotlib, statsmodels, sklearn, scipy
Visualization: Histograms, scatter plots, Q-Q plots, heatmaps
Statistical Techniques: Linear and logistic regression, hypothesis testing, multicollinearity diagnostics
Future Wor
