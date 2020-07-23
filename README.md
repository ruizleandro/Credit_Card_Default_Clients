# Default of Credit Card Clients Project

## Introduction
This projects tries to predict if a client will be to default their payments using data from the last 6 months.

The main objective of this project is to predict if a client of a bank will default their payments using information from the last 6 months.

This project has six sections:

1. Data Cleaning
2. Exploratory Data Analysis
3. Data Preprocessing
4. Model Selection
5. Hyperparameter Tuning
6. Final Test of the Model

In the `Model Selection` section, I am going to use three models:

* Logistic Regression
* Support Vector Machines
* Random Forest Classifier

## Summary of the Exploratory Data Analysis
I drew three conclusions from the data exploration:
* Male clients and those who only are high school graduates are more prone to default their credit card payments.
* More than half of customers with a monthly limit of more than $ 10,000 ends up in default.
* You might think that younger clients would be more likely to default, but the data shows that clients in their 30s are the most likely to default.

## Summary of the Project
As we can see, the model that better performed for this task was the Logistic Regression model, with this results:

* Precision: 0.83
* Recall: 0.95

We have to take into account that the bank may have two different intentions for this data: predict the default of their clients or prevent it.

For this first intention, I should tweak the model so it has fewer false negatives. Thus the bank has more accurate information about the condition of its customers.

And for the second, the bank needs more false positives, so the bank can assist its clients in time and prevent them from going into default.

## Future Work/Next Steps
In the future, I could try more models, like:

* Normalized Linear Regression
  * Ridge Regression
  * Lasso Regression
* Neural Networks

With their respective hyperparameter tuning.

Also, I could use a bigger dataset (+30000 samples), in this way we will have more training examples and the final result of the test will be more reliable.
