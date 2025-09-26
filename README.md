# Logistic-Regression - Breast Cancer Prediction

This project performs binary classification on breast cancer data to predict diagnosis (malignant or benign) using logistic regression.

## Dataset

- The dataset contains features extracted from breast tumor images: radius, texture, perimeter, area, smoothness, compactness, concavity, symmetry, fractal dimension, and more.
- The target variable is `diagnosis` with two classes: **M** (malignant) and **B** (benign).


## Project Overview

- Load and preprocess the data (handle missing values, encode target).
- Scale the feature variables for consistent magnitude.
- Split data into training and testing sets.
- Train a logistic regression model.
- Evaluate model performance using metrics such as accuracy, confusion matrix, classification report.
- Compute and visualize ROC curve and calculate ROC AUC score.
- Tune classification threshold for optimal balance of sensitivity and specificity.
- Visualize the sigmoid activation function and threshold decision boundary.


## Usage

- Run the Jupyter notebook `Logistic-Regression.ipynb` for step-by-step implementation.
- The model outputs predicted probabilities and allows threshold tuning.
- Sigmoid function visualization illustrates the logistic sigmoid curve and classification decision threshold.


## Dependencies

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
