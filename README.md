# Credit Card Fraud Detection using Machine Learning

## Overview

This project aims to detect fraudulent credit card transactions using machine learning classification algorithms. The objective is to identify suspicious transactions by analyzing transaction-related features and comparing the performance of multiple classification models.

The project covers data preprocessing, exploratory data analysis (EDA), model training, and evaluation on a real-world credit card transaction dataset.

---

## Dataset

**Dataset:** [Credit Card Fraud Detection Dataset (Kaggle)](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud?utm_source=chatgpt.com)

### Dataset Summary

* Total Transactions: **284,807**
* Fraudulent Transactions: **492**
* Legitimate Transactions: **284,315**
* Fraud Rate: **0.172%**
* Features: **30 numerical features**
* Target Variable: **Class** (`0` = Legitimate, `1` = Fraud)

### Dataset Description

The dataset contains anonymized credit card transactions made by European cardholders in September 2013. Features `V1`–`V28` are PCA-transformed variables to protect sensitive information, while `Time` and `Amount` remain untransformed. The dataset is highly imbalanced, making it suitable for fraud detection, anomaly detection, and imbalanced classification problems.

---

## Features

* Data Cleaning and Preprocessing
* Exploratory Data Analysis (EDA)
* Class Distribution Analysis
* Multiple Classification Models
* Performance Comparison
* Confusion Matrix Visualization

---

## Machine Learning Models Used

* Logistic Regression
* Support Vector Machine (SVM)
* K-Nearest Neighbors (KNN)
* Decision Tree Classifier

---

## Evaluation Metrics

The models were evaluated using:

* Accuracy
* Precision
* Recall
* Confusion Matrix

---

## Results

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | 97%+     |
| SVM                 | 98%+     |
| KNN                 | 99%+     |
| Decision Tree       | 99%+     |

> Note: Results may vary depending on train-test split and preprocessing techniques.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Credit-Card-Fraud-Detection.git
cd Credit-Card-Fraud-Detection
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

## Usage

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
credit_card_fraud_detection.ipynb
```

Run all cells to reproduce the analysis and model results.

---

## Key Learnings

* Machine Learning Classification
* Handling Imbalanced Datasets
* Exploratory Data Analysis
* Model Evaluation and Comparison
* Fraud Detection Techniques
* Data Visualization

---

## Future Improvements

* Implement SMOTE for class balancing
* Add Random Forest and XGBoost models
* Incorporate SHAP-based explainability
* Build a Streamlit web application
* Deploy the model for real-time predictions

---
