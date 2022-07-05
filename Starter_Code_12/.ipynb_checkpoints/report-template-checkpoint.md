# Module 12 Report Template

## Overview of the Analysis

Classifying credit risk is inherently imbalanced because healthy loans outnumber risky loans. In this machine learning exercise, we used various techniques to determine if certain variables could be used to predict a healthy or unhealthy loan. 

* Steps: 
    * #1 Split data into Training and Testing Sets
    * #2 Create a Logistic Regression Model with the Original Data
    * #3 Predict a Logistic Regression Model with Resampled Training Data

* Variables: Loan size, interest rate, borrower income, debt to income, # of accounts, total debt. 

* Methods used: Logisitic regression model and with resampled data. 

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Precision: 0.86
  * Recall: 0.90
  * f1-score: 0.88
  * Support: 1881


* Machine Learning Model 2:
  * Precision: 0.84
  * Recall: 0.99
  * f1-score: 0.91
  * Support: 619
  
## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* If we are trying to predict 1's (high-risk loans), the fit with the oversampled data does a .03 better job at predicting the true scenarios than the original data.

