# credit-risk-classification

Background

In this Challenge, you’ll use various techniques to train and evaluate a model based on loan risk. You’ll use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

Instructions

The instructions for this Challenge are divided into the following subsections:

Split the Data into Training and Testing Sets

Create a Logistic Regression Model with the Original Data

Write a Credit Risk Analysis Report

Split the Data into Training and Testing Sets

Open the starter code notebook and use it to complete the following steps:

Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.

Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.

Split the data into training and testing datasets by using train_test_split.

Create a Logistic Regression Model with the Original Data

Use your knowledge of logistic regression to complete the following steps:

Fit a logistic regression model by using the training data (X_train and y_train).

Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.

Evaluate the model’s performance by doing the following:

Generate a confusion matrix.

Print the classification report.

Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?

Write a Credit Risk Analysis Report: 

## Overview of the Analysis

Overview: The basis of this anaylsis is to identify the creditworthiness of borrowers by using a dataset of historical lending activity from a peer-to-peer lending services company. The data entailed the size of the loan, interest rate, the income of the borrower, the number of accounts, derogatory marks, total  debt and loan status. Our target variable was the loan status, generally identified with 0s and 1s, 0 being a healthy loan, 1 being a high risk loan. In the original data each count totaled to 75036 for the number of healthy loans, and 2500 for the high-risk loans. To acheive our prediction model, we started with splitting the data into training and testing sets, then we created a logistic regression model to fit the data. 

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Accuracy: 99%
  * Precision: 100% for healthy loans, 85% for high-risk loans 
  * Recall: 99% for healthy loans, 91% for high-risk loans 



* Machine Learning Model 2 (Resampled Data):
  * Description of Model 2 Accuracy, Precision, and Recall scores.
  * Accuracy: 99%
  * Precision: 100% for healthy loans, 84% for high-risk loans 
  * Recall: 99% for healthy loans, 99% for high-risk loans 

## Summary

In summary, the model for the resampled data faired more better than the original data, overall. Mostly the recall score would be the main deciding factor of which model would be best of use. 

