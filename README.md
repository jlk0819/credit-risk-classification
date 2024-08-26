# credit-risk-classification
Create a Logistic Regression Model with the Original Data
Use your knowledge of logistic regression to complete the following steps:

Fit a logistic regression model by using the training data (X_train and y_train).

Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.

Evaluate the model’s performance by doing the following:

Generate a confusion matrix.

Print the classification report.

Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?

Module 12 Report

Overview of the Analysis


The purpose of this analysis is to evaluate the effectiveness of a logistic regression machine learning model for identifying the creditworthiness of borrowers by using a dataset with borrower's current debts and income information to predict whether a loan is healthy or high-risk, and comparing this against a known value as to whether or not the loan is high-risk. This dataset was split into training and testing sets in order to use a Logistic Regression model, and afterwards a confusion matrix was created to view the accuracy, precision, and recall for the model.

Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

•	Machine Learning Model 1: Logistic Regression Model

•	Accuracy: 0.99
•	Precision:
    o	Healthy Loans (0): 1.00
    o  	High-Risk Loans (1): 0.86
•	Recall:
   o	Healthy Loans (0): 1.00
   o	High-Risk Loans (1): 0.91



Summary

With an accuracy of 0.99, and a precision and recall for high-risk loans at or above 0.92 for all scenarios, including being 1.00 when focused on healthy loans, this model performed extremely well with the data. Based on these evaluation metrics, the model is highly recommended for identifying loan statuses. Its high accuracy and strong performance metrics make it a valuable tool for credit risk analysis.