# 🧠 Logistic Regression from Scratch & with scikit-learn

This notebook demonstrates the implementation of **Logistic Regression** using both a **custom-built class** and **scikit-learn**, applied on the *Social_Network_Ads.csv* dataset. It includes full pipeline stages: data preprocessing, exploratory analysis, model training, tuning, and evaluation.

---

## 📑 Table of Contents

1. [Overview](#-overview)  
2. [Dataset](#-dataset)  
3. [Exploratory Data Analysis](#-exploratory-data-analysis)  
4. [Feature Engineering & Scaling](#-feature-engineering--scaling)  
5. [Logistic Regression from Scratch](#-logistic-regression-from-scratch)  
6. [Hyperparameter Tuning](#-hyperparameter-tuning)  
7. [Model Comparison](#-model-comparison)  
8. [Evaluation Metrics](#-evaluation-metrics)  
9. [Conclusion](#-conclusion)

---

## 🔍 Overview

This project builds a binary classification model to predict user purchase behavior on a social network platform based on features like **Age** and **Estimated Salary**. Two logistic regression models are explored:

- ✅ From-scratch implementation using NumPy  
- 🛠️ Scikit-learn implementation with hyperparameter tuning

---

## 📂 Dataset

- Source: `Social_Network_Ads.csv`  
- Features used:
  - Age
  - Estimated Salary  
- Target: Purchased (Binary class: 0 or 1)

---

## 📊 Exploratory Data Analysis

Includes:
- Gender-based distribution of salary and age
- Purchase patterns by gender
- Correlation heatmaps
- Multivariate plots with Seaborn & Matplotlib

---

## 🧪 Feature Engineering & Scaling

Steps:
- Encoding categorical variables  
- Standardizing numerical features  
- Splitting data into training and test sets

---

## 🏗️ Logistic Regression from Scratch

A custom class `LogisticRegressionScratch` is defined and trained using gradient descent. It includes:
- Sigmoid function  
- Cost function (Binary Cross-Entropy)  
- Gradient computation and parameter update logic  
- Training loop with accuracy tracking

---

## 🧪 Hyperparameter Tuning

- Conducted Grid Search for scikit-learn model
- Evaluated various regularization parameters and solvers

---

## 📈 Model Comparison

- Compared the performance of:
  - Custom implementation  
  - scikit-learn’s `LogisticRegression`

---

## 📊 Evaluation Metrics

- Confusion Matrix
- Precision-Recall Curve
- Accuracy Score
- Classification Report

---

## 📝 Conclusion

This notebook demonstrates the practical implementation of logistic regression from theoretical concepts to a real-world application. It reinforces understanding of model behavior, training dynamics, and evaluation metrics.

                                ---

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

### ✨ Contributions Welcome!
