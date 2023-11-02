# Module 12 Report Template

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


