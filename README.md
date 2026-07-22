# 🏡 Surprise Housing Price Prediction using Ridge & Lasso Regression

## Overview

This project builds regularized regression models to predict housing prices for an Australian housing dataset. The objective is to help Surprise Housing identify undervalued properties for investment using machine learning.

The project compares **Ridge Regression** and **Lasso Regression**, performs hyperparameter tuning using cross-validation, and identifies the most influential factors affecting house prices.

---

## Business Problem

Surprise Housing, a US-based real estate company, plans to enter the Australian housing market.

The goal is to build a predictive model that estimates house prices using historical property data. The model helps the company:

- Identify undervalued properties
- Understand factors influencing house prices
- Support data-driven investment decisions
- Improve profitability through informed purchasing

---

## Dataset

- Australian Housing Dataset
- Target Variable: **SalePrice**
- Multiple numerical and categorical features describing each property

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Machine Learning Workflow

1. Data Understanding
2. Data Cleaning
3. Missing Value Treatment
4. Exploratory Data Analysis
5. Feature Engineering
6. Encoding Categorical Variables
7. Train-Test Split
8. Feature Scaling
9. Ridge Regression
10. Lasso Regression
11. Hyperparameter Tuning using Cross Validation
12. Model Evaluation
13. Feature Importance Analysis

---

## Models Used

### Ridge Regression

- L2 Regularization
- Hyperparameter tuning using Cross Validation
- Reduces overfitting while retaining all variables

### Lasso Regression

- L1 Regularization
- Performs automatic feature selection
- Produces a simpler and more interpretable model

---

## Evaluation Metrics

- R² Score
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

---

## Key Results

- Built both Ridge and Lasso regression models.
- Determined the optimal alpha value using cross-validation.
- Compared model performance.
- Identified the most significant predictors affecting house prices.
- Demonstrated the effect of regularization on model complexity.

---

## Repository Structure

```text
surprise-housing-price-prediction/
│
├── data/
├── notebooks/
├── reports/
├── images/
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore
```

---

## Future Improvements

- Deploy the model using Streamlit or Flask
- Experiment with Elastic Net Regression
- Compare with tree-based regression models
- Perform advanced feature selection techniques

---

## Author

**Hanaa Parvez Khan**

M.Sc. Data Science | Data Analytics | Machine Learning | Python | SQL
