# Project Title

A brief description of the project.

## Description

This project involves cleaning, transforming, and analyzing a dataset to prepare it for machine learning model building. It focuses on handling duplicates, missing values, outliers, skewness, and feature selection. The project also includes balancing the target class distribution and implementing several machine learning models for predictive tasks.

## Features

1. Handles duplicate rows and missing values.
2. Extracts individual components from timestamp data.
3. Encodes categorical columns and standardizes numerical columns.
4. Handles outliers and transforms data to a normal distribution.
5. Selects the top features for modeling.
6. Balances target class distribution using SMOTE and Random UnderSampling.
7. Splits data into training and testing sets.
8. Implements multiple machine learning models.

---

## Dependencies

The project relies on the following Python libraries:
- `pandas`
- `numpy`
- `seaborn`
- `matplotlib`
- `sklearn` (Scikit-learn)
- `imblearn` (for SMOTE and RandomUnderSampler)
- `xgboost`
- `scipy`

To install the dependencies, use the following command:
```bash
pip install pandas numpy seaborn matplotlib scikit-learn imbalanced-learn xgboost scipy
