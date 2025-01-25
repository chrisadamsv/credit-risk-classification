# credit-risk-classification
Use various techniques to train and evaluate a model based on loan risk using a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

## Overview of the Analysis
The purpose of this analysis is to create a supervised machine learning model to analyze various variables on loans marked "healthy" or "high-risk" to predict how future loans will become delinquent. The model analyzes the size of the loan, the interest rate, the borrower's income, their dept to income ratio, their total number of accounts, their total derogatory marks on their credit, and their total debt. The model created is a logistic regression model using the aforementioned factors against the status of the loan (delinquent/healthy). The results of the model are as follows: 

## Results
* Confusion Matrix:
    * Healthy Loan Predictions:
        * 18673 TN
        * 86 FP
    * High-Risk Predictions:
        * 593 TP
        * 32 FN

* Classification Report:
    * Accuracy: 99% (0.99) 
    * Precision: 
        * Healthy Loan: 100% (1.00)
        * High-Risk Loans: 87% (0.87)
    * Recall:
        * Healthy Loan: 100% (1.00)
        * High-Risk Loans: 95% (0.95)

## Summary
The model does exceptionally well at using risk factors to predict whether a loan will be healthy or high-risk. The overall model accuracy is 99%. The bank would have a near perfect rate of predicting that a loan will end up healthy. The only downside is that it is slightly less accurate at predicting if a loan will end up high-risk. This could result in people losing out on economic opportunity when they shouldn't. However for the bank's interests, this could result in them approving more high interest loans to people who will pay them, generating more revenue for the bank. 

