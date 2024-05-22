# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.

-- The goal of this analysis was to predict the likelihood of a loan being approved or rejected based on various financial factors.

* Explain what financial information the data was on, and what you needed to predict.

-- The dataset contained information on loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt. The target variable we needed to predict was loan_status (approved or rejected).


* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).

We were predicting the loan_status, which had two possible values: 0 for rejected and 1 for approved loans. Here's a basic breakdown of the target variable:

`y.value_counts()` This will show how many loans were approved vs. rejected.

* Describe the stages of the machine learning process you went through as part of this analysis.
Data Loading: Reading the data from CSV into a DataFrame.
Data Preprocessing: Separating the features (X) and the labels (y).
Data Splitting: Dividing the data into training and testing sets.
Model Training: Using Logistic Regression to train the model on the training data.
Model Prediction: Making predictions on the test data.
Model Evaluation: Evaluating the model's performance using metrics like accuracy, precision, and recall.


-- 
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).

The method used is LogisticRegression from the sklearn library to build and train the model.


## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.

 Machine Learning Model 1 (Logistic Regression):
- Accuracy: How often the model correctly predicts loan approval or rejection.
- Precision: The proportion of true positive predictions (correctly predicted approvals) out of all positive predictions (all predicted approvals).
- Recall: The proportion of true positive predictions out of all actual positives (all actual approvals).   

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best?
- The Logistic Regression model performed well, with high accuracy, precision, and recall scores.
- Based on these metrics, Logistic Regression appears to be a reliable model for predicting loan approval status.

* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.

- Logistic Regression is recommended as it performed well in predicting whether a loan would be approved or rejected. It provided high accuracy, meaning it correctly predicted the outcome most of the time. Additionally, it had good precision and recall scores, indicating it was reliable in both identifying approved loans and avoiding false approvals. Overall, Logistic Regression was a strong, balanced model for this task.