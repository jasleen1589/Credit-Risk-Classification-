# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* The purpose of this analysis is to develop a machine learning model to understand credit lending and the risks associated with it.
* The dataset included information on loan size, interest rate, borrower income, debt-to-income ratio, number of accounts for the consumer, derogatory marks on the credit history, total debt of the consumer, and the loan status.
* Variables I tried to predict were Healthy Loan which was characterized as the value of "0" and High-Risk Loan which was characterized as the value of "1". 
* The stages I went through were analyzing the data, preprocessing it, and then applying the Logisitic Regression model as part of the Machine Learning Process for this assignment. 

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Description of Model 0: Healthy Loans
     Accuracy - Model achieved 99% of accuracy indicating that 99% of the predictions matched the actual loan statuses.
     Precision - Precision for predicting healthy loans was 100% suggesting that when the model predicted a loan was healthy, it was accurate 100% of the time. 
     Recall scores - Recall score was 99% for Healthy Loans which means that the model correctly identified 99% of all healthy loans. 

* Description of Model 1: High-Risk Loans
     Accuracy - Model achieved 99% of accuracy indicating that 99% of the predictions matched the actual loan statuses.
     Precision - Precision for predicting High Risk loans was 85% suggesting that when the model predicted a loan was high risk, it was accurate 85% of the time. 
     Recall scores - Recall score was 91% for High Risk Loans which means that the model correctly identified 91% of all high risk loans. 

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* The model that has higher precision, recall, and accuracy would be considered the best which would be the High Risk Loan. I believe it would be so because that model would be more reliable with it's predictions, make fewer mistakes, and help ensure that all factors are evaluated when making a credit risk assessment.
* Assuming all the factors are accurately studied in the machine learning model, more 1's would be of higher value. Not to say that would be the best way to go but it is better to have false positive values and investigate further and understand how that situation can be fixed or any intervention that would help it improve compared to all good values such as healthy loans and setting yourself for failure with higher credit risk assessments which could eventually cause issues such as loan defaults. 


