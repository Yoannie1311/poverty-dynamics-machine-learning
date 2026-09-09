# Machine Learning Analysis of Poverty Dynamics and Euro Adoption in Eastern Europe

## Overview

This repository contains the code accompanying my MSc Data Science & Society thesis completed at Tilburg University.

The research investigates whether machine learning models can accurately predict the **At-Risk-of-Poverty Rate (AROP)** using socioeconomic indicators in Eastern European countries, while exploring poverty dynamics within the context of Eurozone integration.

---

## Research Objectives

This project aims to:

- Predict poverty rates using machine learning techniques.
- Compare the performance of Linear Regression, Support Vector Regression (SVR), and Random Forest Regression.
- Identify the socioeconomic indicators most strongly associated with poverty.
- Improve model interpretability using Explainable Artificial Intelligence (SHAP).
- Explore poverty dynamics surrounding euro adoption.

---

## Dataset

The dataset was manually compiled from publicly available Eurostat and OECD data.

Countries included:

- Bulgaria
- Croatia
- Lithuania
- Poland

Time period:

**2014–2025**

Target variable:

- At-Risk-of-Poverty Rate (AROP)

Predictor variables:

- Unemployment
- Inflation
- GDP Growth
- Gini Coefficient
- Housing Burden
- Ability to Face Unexpected Expenses
- Euro Adoption Status

---

## Methodology

The workflow consists of:

- Data collection and integration
- Data preprocessing
- Exploratory Data Analysis (EDA)
- Feature scaling
- Time-based train/test split
- Bayesian hyperparameter optimisation
- Model evaluation
- SHAP explainability analysis

---

## Models

- Linear Regression
- Support Vector Regression (SVR)
- Random Forest Regression

Support Vector Regression and Random Forest were optimised using Bayesian hyperparameter optimisation.

---

## Evaluation

Model performance was evaluated using:

- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)
- R² Score

The models were evaluated using a chronological train-test split to preserve the temporal structure of the data.

---

## Results

The optimised Support Vector Regression model achieved the strongest predictive performance, while SHAP analysis identified inequality (Gini coefficient), financial vulnerability, and unemployment as the most influential predictors of poverty outcomes.  [oai_citation:1‡Y.Petrova - ThesisFinalDraft.pdf](sediment://file_00000000064c82108e4524669c637a91)

---

## Technologies

- Python
- pandas
- NumPy
- scikit-learn
- SHAP
- scikit-optimize
- matplotlib
- scipy
- statsmodels
- Jupyter Notebook

---

## Repository Contents

Currently this repository contains the complete notebook used for data preprocessing, model development, evaluation, and explainability analysis.

Future updates will include a cleaner project structure with separated notebooks, figures, and documentation.

---

## Thesis

**Machine Learning Analysis of Poverty Dynamics and Euro Adoption in Eastern Europe**

MSc Data Science & Society

Tilburg University

---

## Author

Yoana Petrova
