# Analysis report

## Overview

Create a model to predict and identify the risk of future loan applicants:

* Using a dataset containing historical lending data from a peer to peer lending services company, a model was built to evaluate and identify the risk of future borrowers.
* The purpose is to create and evaluate the accuracy of a data model designed to predict the credit worthiness of future borrowers. 
* The data contained information in relation to the 'loan size', 'interest rate', 'borrower income', 'debt to income ratio', 'number of accounts' of the borrower, 'total debt' and 'derogatory marks' where we are assessing 'loan status'.
* The loan status tells us the approval status of the loan and this is the data predicated in the model.
* Firstly the csv file was read into a dataframe, the training and test data was separated and then a logistic regression model was created with the original datausing sckit learn. The resampled training data was used to predict a logistical regression model and from this, a comprehensive analysis report showing the credit risk was created.

## Results

Analysis of the balanced accuracy, precision and recall scores of the machine learning model.

* Machine Learning Model 1:
  * __Balanced Accuracy__ The balanced accuracy score of the model was 95.2% meaning it considers all sensitivity ie; true positive rate or recall and specificity (true negative) of the model
  * __Recall__ 95% accurate prediction of the true positive values of the positive predictions were made
  * __Precision__ 92% of the predicted positive outcomes were correct



## Summary and recommendation


* The model is on average, 100% precise when predicting low-risk loans (0) however when it comes to high risk loans (1), the precision is 85% which is not a high enough score to use without some human intervention.
* In the event that the model is used for low-risk loans, I would recommend it as the balanced accuracy sits just over 95% which means it accurately predicts the credit worthiness of borrowers and predicting the ability to repay the loan. From this, the accuracy range could be fit to different business profiles to ensure lenders have an appropriate capital flow and the model can be relied upon. In the interest of high-risk loans, I would not recommend this model as there is a 15% margin for error.


