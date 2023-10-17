# Credit Risk Calculation challenge using machine learning
Training and evaluating a model based on loan risk.

<img width="1440" alt="Belly button cleaning" src="https://github.com/Tarynfo1/belly-button-challenge/blob/392a69e46dcbf6a7225bef728568b1e3a9326be7/Images/bellybuttonclean.png">

*** 
## Description
Using machine learning and pandas modules to train and evaluate a model of loan risk. The dataset contains historical lending activity from a peer-to-peer lending company and assesses the credit risk associated with each borrower.

***
## File structure
- __Resources:__ contains lending_data.csv file and images for readme file
- __credit_risk_classification.ipynb:__ Python code
- __README.md:__ ReadMe file, you're already here
- __Analysis report:__ Full analysis of csv file data

***
## Tools
- Python
- pandas
- Scikit learn
***
## Instructions
1. The data is split into separate training and test sets.

 2. A logistical regression model was created using the original data 
    
    <img width="366" alt="bar_chart" src="https://github.com/Tarynfo1/belly-button-challenge/blob/392a69e46dcbf6a7225bef728568b1e3a9326be7/Images/bar_chart.png">

 3. Used the resampled training data to create a predictive logistic regression model
    
    <img width="913" alt="bubble_chart" src="https://github.com/Tarynfo1/belly-button-challenge/blob/392a69e46dcbf6a7225bef728568b1e3a9326be7/Images/bubble_chart.png">

  4. Create a report to analyse the resulting data.
 
***
## Acknowledgements
- https://plotly.com/python/reference/indicator/#indicator-gauge-axis-dtick assisted in the following code snippet
```
# Generate a confusion matrix for the model

cf_test_matrix = confusion_matrix(y_test, test_predictions)

cf_test_matrix
```

