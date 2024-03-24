# Multi-Class Prediction of Obesity Risk

## Introduction
In this project, our goal is to predict the risk of obesity using machine learning algorithms. The dataset we're working with contains valuable information about individuals' demographic details, lifestyle habits, and physical characteristics.

# Data Exploration
## Creating DataFrame
We begin by loading the dataset into a pandas DataFrame, dropping the 'id' column as it's redundant for our analysis.

## Dimensions of the DataFrame
Checking the dimensions of the DataFrame helps us understand its size and structure.

## Displaying the First 20 Rows
Examining the first few rows of the DataFrame gives us an initial insight into the data.

# Data Preprocessing
## Creating Dummies
To handle categorical variables, we convert them into dummy variables using one-hot encoding, facilitating model training.

## Data Partitioning
Splitting the dataset into training and validation sets allows us to effectively train and evaluate our models.

# Modelling Techniques
## Random Forest Classifier
We train a Random Forest Classifier model and evaluate its performance using accuracy metrics and a confusion matrix.

## Decision Tree Classifier
Similar to the Random Forest Classifier, we train and evaluate a Decision Tree Classifier to predict obesity risk.

## MLP Classifier
Employing a Multi-Layer Perceptron (MLP) Classifier, we assess its accuracy in predicting obesity risk.

## Gradient Boosting Classifier
A Gradient Boosting Classifier model is trained and evaluated, showing promising results with high accuracy.

# Testing
## Predictions on Test Data
We utilize the trained Gradient Boosting Classifier to make predictions on the test dataset, saving the results for submission.

# Conclusion
In this project, we explored various machine learning algorithms to predict the risk of obesity based on demographic and lifestyle factors. The Gradient Boosting Classifier emerged as the best-performing model, achieving a high accuracy level of .90 in predicting obesity risk. This predictive capability can potentially aid in early intervention and preventive healthcare measures.




