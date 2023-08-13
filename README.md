# revelo
# Credit Card Fraud Detection

## Overview

This repository contains a credit card fraud detection project using machine learning techniques. The project focuses on predicting fraudulent credit card transactions based on historical data. A logistic regression model is trained and evaluated to achieve accurate fraud detection.

## Dataset

The dataset used in this project is the [Credit Card Fraud Detection Dataset] available on Kaggle. The dataset is highly imbalanced, with a large number of legitimate transactions and a small number of fraudulent transactions.

## Packages Used

- pandas
- scikit-learn
- numpy
- matplotlib (for visualization)
- seaborn (for visualization)

## Steps

1. **Data Loading and Exploration:**
   - Load the dataset using `pandas`.
   - Explore the distribution of the target variable ('Class') to understand the class imbalance.

2. **Data Preprocessing:**
   - Handle missing values by filling them with the mean of respective columns.
   - Apply label encoding to the target variable 'Class' to convert it into numeric values.

3. **Data Splitting and Standardization:**
   - Split the dataset into training and testing sets using `train_test_split`.
   - Standardize the features using `StandardScaler` to ensure consistent scaling for modeling.

4. **Model Building and Training:**
   - Create a logistic regression model using `LogisticRegression` from scikit-learn.
   - Train the model on the scaled training data.

5. **Model Evaluation:**
   - Make predictions on the scaled testing data.
   - Evaluate the model's performance using accuracy score and classification report.

6. **Results and Insights:**
   - Achieve high accuracy in fraud detection using logistic regression.
   - Analyze the classification report to understand precision, recall, and F1-score for both classes.

## Instructions to Use

1. Clone the repository to your local machine.
2. Ensure you have the required packages by using the command:
