# Credit Risk Calculation challenge using machine learning
Training and evaluating a model based on loan risk.

<img width="1440" alt="Belly button cleaning" src="https://github.com/Tarynfo1/credit-risk-classification/blob/c1d14fe59eeafc9b9def13852ce72a15411f7be6/Resources/title_image.jpg">

*** 
## Description
Using machine learning and pandas modules to train and evaluate a model of loan risk. The dataset contains historical lending activity from a peer-to-peer lending company and assesses the credit risk associated with each borrower.

***
## File structure
- __Resources:__ contains lending_data.csv file and images for readme file
- __credit_risk_classification.ipynb:__ Python code
- __README.md:__ ReadMe file, you're already here
- __Analysis report:__ Full analysis of csv file data and recommendations on usage of the model

***
## Tools
- Python
- pandas
- Scikit learn
***
## Instructions
1. The data is split into separate training and test sets.

2. A logistical regression model was created using the original data 
    
    <img width="366" alt="bar_chart" src="https://github.com/Tarynfo1/credit-risk-classification/blob/a98de1eee9ed0a77bc50746eef75e268bb3c0eac/Resources/M21_logisticalregres.png">

  4. A report was created to analysis the models predictive ability.
 
***
## Acknowledgements
- https://www.w3schools.com/python/python_ml_confusion_matrix.asp assisted in the following code snippet
```
# Generate a confusion matrix for the model

cf_test_matrix = confusion_matrix(y_test, test_predictions)

cf_test_matrix
```

