# Module 12 Report Template

## Overview of the Analysis

The purpose of the analysis is to use machine learning to distinguish between health and hig-risk loan so that in the future, financial company would have manage the loan application more accurate.

We used a dataset for loan and borrower detail such as loan amount, interest rate, borrower's income, histpry of opened account, and debt information. 

We have total of 18384 data in this dataset and we use the lofistic Regression algorithm in this machine learning. Logistic Ression is a method that is good for binary classification, Since we are just testing for healthy or high rist loan, this is a great method for this exercisce. We first import the data and clean and prepare the data for modeling. Then we identifying the features to use for prediction and train the model. After that we evalusate and obtain the conclusion.

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.

Healthy loan data
Precision: 1.00
Recall: 1.00
f1-score: 1.00
support: 18759

High Risk loan data
Precision: 0.87
recall: 0.89
f1-score: 0.88
support: 625

## Summary

In conclusion, it does a good job in predicting healthy loan, it has 100% precision and 100% recall which mean it does not miss any healthy loan when running the model. F1-scores also shows that the prediction for healthy loan is perfect.

For the High risk loan, there might need an improvemnt to it, the precision rate is around 87% and recall rate is around 89%. which means the model can predict 87% of high risk loan and it does miss some of the high risk loan while running the model. F1-score at 0.88, that means balance between precision and recall are pretty good.

