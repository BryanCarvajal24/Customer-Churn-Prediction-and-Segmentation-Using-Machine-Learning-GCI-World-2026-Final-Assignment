# Customer Churn Prediction and Segmentation Using Machine Learning

## Overview

This repository contains the Final Assignment developed for **GCI World 2026**, focused on solving one of the most critical challenges in the telecommunications industry: customer churn.

The project combines **predictive analytics** and **customer segmentation** techniques to identify customers at risk of leaving the company and support data-driven retention strategies. Using a large-scale telecommunications dataset containing customer demographics, service usage, revenue information, network quality indicators, and device characteristics, multiple machine learning models were developed and evaluated.

## Objectives

- Predict customer churn probability.
- Identify behavioral customer segments.
- Understand the main drivers of churn.
- Support proactive customer retention strategies.
- Improve Customer Lifetime Value (CLV) and reduce revenue loss.

## Dataset

The dataset contains approximately 100,000 customer records and includes:

- Customer demographics
- Revenue and billing information
- Service usage metrics
- Network quality indicators
- Device characteristics
- Churn status

### Target Variable

- **0** → Customer Remains
- **1** → Customer Leaves

## Methodology

### Exploratory Data Analysis (EDA)

The analysis focused on:

- Missing value assessment
- Outlier detection and treatment
- Correlation analysis
- Distribution analysis
- Churn behavior exploration
- Feature importance analysis

### Data Preparation

The preprocessing workflow included:

- Numerical missing value imputation
- Categorical missing value treatment
- Feature selection
- Outlier handling
- Categorical encoding
- Feature engineering

## Machine Learning Models

Several classification algorithms were evaluated:

- Logistic Regression
- XGBoost
- CatBoost
- LightGBM
- Voting Ensemble

### Best Performing Model

**XGBoost** achieved the best overall predictive performance and was selected as the final churn prediction model.

## Customer Segmentation

In addition to churn prediction, customer segmentation was performed using:

- K-Means++

Three distinct customer groups were identified:

1. Established Family Customers
2. High-Value Power Users
3. Low-Commitment Individual Customers

These segments provide additional business insights for targeted retention campaigns and personalized customer engagement strategies.

## Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Business Impact

The proposed solution enables telecommunications companies to:

- Reduce customer churn
- Increase customer retention
- Improve Customer Lifetime Value (CLV)
- Optimize marketing investments
- Enhance customer targeting strategies
- Preserve recurring revenue streams

## Author

**Bryan Fernando Burbano Carvajal**

GCI World 2026 – Final Assignment
