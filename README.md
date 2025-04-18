# Logistic Regression from Scratch

This project implements **Logistic Regression** from the ground up using only NumPy, without relying on high-level machine learning libraries like scikit-learn or TensorFlow. It's intended as an educational tool to understand the inner workings of logistic regression, including model training using gradient descent.

## Features

- Implementation of logistic regression for binary classification.
- Uses sigmoid activation and cross-entropy loss.
- Includes gradient descent optimization.
- Code is written in Python using only NumPy for numerical operations.
- Visualizations and model performance evaluation included.

## Dataset

The dataset used in this project is the **Churn_Modelling.csv**, which contains customer data from a bank and is used for binary classification (whether a customer will churn or not).

- You can download it from Kaggle:  
  [Bank Churn Dataset - LightGBM Classification Notebook](https://www.kaggle.com/code/aspillai/bank-churn-dataset-classification-lightgbm/input?select=Churn_Modelling.csv)

- Features include customer demographics, account balance, tenure, number of products, and more.

## Notebook Contents

- **Data Preparation**: Loading and preprocessing the dataset.
- **Model Implementation**: Custom logistic regression class/functions.
- **Training & Evaluation**: Model training using gradient descent and accuracy/loss tracking.
- **Visualization**: Decision boundaries, loss curves, and prediction plots.

## Getting Started

### Prerequisites

- Python 3.x
- NumPy
- Matplotlib (for visualization)
- Jupyter Notebook or a compatible environment

### How to Run

1. Clone the repository or download the notebook.
2. Install the required libraries:
   ```bash
   pip install numpy matplotlib
   ```
3. Download the dataset from the [Kaggle link](https://www.kaggle.com/code/aspillai/bank-churn-dataset-classification-lightgbm/input?select=Churn_Modelling.csv) and place it in the same directory as the notebook.
4. Open the notebook:
   ```bash
   jupyter notebook logistic-regression-from-scratch.ipynb
   ```
5. Run each cell in order to follow the workflow from data preparation to model evaluation.

## License

This project is licensed under the MIT License - see the [LICENSE](#license) section below for details.

