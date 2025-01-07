# Microsoft: Classifying Cybersecurity Incidents with Machine Learning

This repository contains the implementation of a machine learning project to classify cybersecurity incidents as `True Positive (TP)`, `Benign Positive (BP)`, or `False Positive (FP)` using Microsoft's GUIDE dataset. The project aims to enhance the efficiency of Security Operation Centers (SOCs) by automating incident triage and improving enterprise security management.

---

## Project Overview

- **Domain**: Cybersecurity and Machine Learning
- **Dataset**: GUIDE Dataset (contains evidence, alerts, and incidents for cybersecurity triage)
- **Objective**: Develop a robust classification model to predict the triage grade of incidents using historical evidence and customer responses.
- **Business Impact**:
  - Automating triage in SOCs for quicker threat detection.
  - Reducing false positives and prioritizing critical incidents.
  - Enabling guided response systems for effective incident management.

---

## Notebooks

### 1. **`microsoft.ipynb`** (Training Dataset)
This notebook processes the **training dataset** and covers:
- **Data Preprocessing**: Handling missing data, encoding categorical features, and feature engineering.
- **Exploratory Data Analysis (EDA)**: Analyzing patterns, correlations, and class imbalances.
- **Model Training**: Training various machine learning models (e.g., Logistic Regression, Random Forest, XGBoost).
- **Hyperparameter Tuning**: Optimizing model performance using techniques like Grid Search or Random Search.
- **Model Evaluation**: Analyzing performance metrics like Macro-F1 Score, Precision, and Recall on the training dataset.

### 2. **`microsoft_test.ipynb`** (Test Dataset)
This notebook processes the **test dataset** and focuses on:
- **Model Testing**: Applying the trained model to the test dataset.
- **Evaluation**: Evaluating performance metrics (Macro-F1 Score, Precision, Recall) on unseen data.
- **Visualization**: Plotting results for deeper insights and error analysis.

---

## Key Technical Skills

- **Machine Learning**: Classification algorithms, model evaluation (Macro-F1 Score, Precision, Recall).
- **Data Preprocessing**: Handling missing data, feature engineering, encoding techniques.
- **Handling Imbalanced Datasets**: Using SMOTE, adjusting class weights.
- **Cybersecurity**: Frameworks like MITRE ATT&CK, threat detection concepts.
- **Python Libraries**: Pandas, NumPy, Scikit-learn, XGBoost, LightGBM, Matplotlib, Seaborn.
- **Model Optimization**: Hyperparameter tuning and cross-validation.

---

## Dataset Structure

The dataset consists of three hierarchies:
1. **Evidence**: Contains supporting metadata (e.g., IP address, user details).
2. **Alerts**: Consolidates multiple pieces of evidence into broader context.
3. **Incidents**: Represents security breaches or threat scenarios with triage grades (TP, BP, FP).

---

## How to Run the Project

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/microsoft-cybersecurity-classification.git
