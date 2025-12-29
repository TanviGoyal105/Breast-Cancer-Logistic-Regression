# Breast Cancer Prediction - Logistic Regression Model

## Overview
This project implements a logistic regression model to classify breast tumors as malignant or benign based on tumor size and other diagnostic features. The goal is to demonstrate a complete, interpretable machine learning workflow for binary classification using a real world medical dataset.

## Files in This Repository
* `BreastCancer-Logistic-Regression.ipynb`
  Jupyter Notebook containing data exploration, preprocessing, model training, and evaluation.
* `data.csv`
  Dataset used for training and testing the model. It contains tumor related metrics and a target label indicating whether the tumor is malignant or benign.

## Dataset
The dataset includes numerical features derived from tumor measurements such as size and related statistical metrics. These features are used as inputs to the logistic regression model to predict tumor classification.

## Methodology

1. Load and inspect the dataset
2. Perform basic data cleaning and preprocessing
3. Split the data into training and testing sets
4. Train a logistic regression classifier
5. Evaluate model performance using standard classification metrics

## Model

* Algorithm: Logistic Regression
* Task: Binary classification (malignant vs benign)
* Output: Probability and class prediction for tumor malignancy

Logistic regression was chosen for its simplicity, interpretability, and effectiveness for binary classification problems in medical applications.

## Results

Model performance is evaluated using metrics such as accuracy and a confusion matrix. Results demonstrate that logistic regression can effectively distinguish between malignant and benign tumors using the provided features.

## How to Run

1. Clone this repository
2. Install Python with common data science libraries (numpy, pandas, matplotlib, etc.)
3. Open the Jupyter Notebook
4. Run all cells to reproduce the results

## Dependencies

* Python 3
* NumPy
* Pandas
* Matplotlib
* scikit-learn
* Jupyter Notebook
