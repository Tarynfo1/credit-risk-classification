# Credit Risk Calculation challenge using machine learning
## To lend, or not to lend - Training and evaluating a machine learning model to assess financial loan risk.

<img width="1440" alt="Belly button cleaning" src="https://github.com/Tarynfo1/credit-risk-classification/blob/c1d14fe59eeafc9b9def13852ce72a15411f7be6/Resources/title_image.jpg">

*** 
## Description
Using machine learning and pandas modules to train and evaluate a model of loan risk. The dataset contains historical lending activity from a peer-to-peer lending company and assesses the credit risk associated with each borrower.

***
## File structure
- __Resources:__ contains lending_data.csv file and images for readme file
- __credit_risk_classification.ipynb:__ credit risk analysis code
- __README.md:__ ReadMe file, you're already here
- __Analysis report:__ Full analysis of csv file data and recommendations on usage of the model

***
## Tools
- Python
- pandas
- Scikit learn
***
## Instructions
1. The training data set is split into separate training and test sets.

2. A logistical regression model was created using the original data in Scikit learn. The purpose of the model is to determine if a loan would be considered high or low risk to the lender.  
    
    <img width="366" alt="bar_chart" src="https://github.com/Tarynfo1/credit-risk-classification/blob/a98de1eee9ed0a77bc50746eef75e268bb3c0eac/Resources/M21_logisticalregres.png">

  4. A report was created to analysis the models predictive ability and recommendations to the lender on the models use.
 
***
## Acknowledgements
- https://www.statology.org/balanced-accuracy-python-sklearn/ assisted in the following code snippet
```
# Print the balanced_accuracy score of the model
logistic_acc_score = balanced_accuracy_score(y_test, test_predictions)
print(logistic_acc_score)
```

