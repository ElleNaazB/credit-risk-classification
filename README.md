This project is about developing and evaluating machine learning models to predict the likelihood of a loan being classified as healthy (0) or high-risk (1) based on various financial factors. The aim is to create a reliable predictive model that lending institutions can use to assess credit risk and make informed decisions.

## Goal of the Analysis:
The goal of this analysis was to predict the likelihood of a loan being approved or rejected based on various financial factors.

## Financial information/data and what needs to be predicted:

The dataset contained information on loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt. The target variable we needed to predict is loan_status (approved or rejected).

## Basic info about the variables being predicted

The loan_status is being predicted in this project and it has teo possible values: 0 for rejected and 1 for approved loans. The basic breakdown of the target variable:
`y.value_counts()` This will show how many loans were approved vs. rejected.


## The Stages of the Machine Learning Proces 

`Data Loading:` Reading the data from CSV into a DataFrame.

`Data Preprocessing:` Separating the features (X) and the labels (y).

`Data Splitting:` Dividing the data into training and testing sets.

`Model Training:` Using Logistic Regression to train the model on the training data.

`Model Prediction:` Making predictions on the test data.

`Model Evaluation:` Evaluating the model's performance using metrics like accuracy, precision, and recall.
