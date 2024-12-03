# Credit Card Fraud Detection Using Machine Learning 💳🔍

## Overview 📊
This project focuses on detecting fraudulent credit card transactions using machine learning techniques. By leveraging a real-world dataset, the project aims to develop a highly accurate predictive model for identifying fraudulent transactions, enhancing financial security.

## Features ✨
- Comprehensive data analysis and preprocessing to prepare the dataset for machine learning.
- Development of machine learning models using Python and evaluation of their performance.
- Visualization of patterns and anomalies in transaction data.

## Dataset 📈
The dataset used in this project is publicly available on Kaggle:  
[Online Payments Fraud Detection Dataset](https://www.kaggle.com/datasets/rupakroy/online-payments-fraud-detection-dataset) 🗂️

### Dataset Features:
- **Time**: Seconds elapsed between this transaction and the first transaction in the dataset.
- **Amount**: Transaction amount.
- **Class**: Indicator of whether the transaction is fraudulent (1) or legitimate (0).
- Additional anonymized features derived from PCA (e.g., `V1`, `V2`, ..., `V28`).

## Workflow 🛠️
1. **Data Loading**: Import the dataset and explore its structure and distribution.
2. **Data Preprocessing**: Clean the data, handle any missing values, scale features, and split the dataset into training and testing sets.
3. **Exploratory Data Analysis (EDA)**:
   - Examine correlations and visualize feature distributions.
   - Identify class imbalances and employ strategies to address them.
4. **Model Building**: Train multiple machine learning models:
   - Logistic Regression 🤖
   - Decision Trees 🌳
   - Random Forests 🌲
5. **Evaluation**: Measure model performance using metrics such as:
   - Accuracy ✅
   - Precision 🎯
   - Recall 🔁
   - F1-score 📏

## Results 🏆
The best-performing model achieved an outstanding **accuracy of 0.9997**, indicating a high level of precision in detecting fraudulent transactions while minimizing false positives and negatives. 🎉

## Tools and Libraries 🧰
- Python 🐍
- `pandas`, `NumPy` for data manipulation
- `Seaborn`, `Matplotlib` for data visualization
- `scikit-learn` for machine learning model training and evaluation
