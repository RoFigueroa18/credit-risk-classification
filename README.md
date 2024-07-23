# credit-risk-classification

Module 20 Challengue

Credit Risk Classification
Overview
This project involves using various machine learning techniques to train and evaluate a model for predicting loan risk. The primary goal is to assess the creditworthiness of borrowers using a dataset of historical lending activity from a peer-to-peer lending services company.

Background
The analysis aims to evaluate the feasibility of using a logistic regression model to classify loans as either healthy or high-risk. This classification assists the lending company in making informed loan approval decisions and managing potential risks.

Steps Performed
1. Data Preparation
Loading the Data
The dataset was loaded into a Pandas DataFrame.

Creating Labels and Features
The target variable was created from the loan status column.
The feature set was created from the remaining columns.
Splitting the Data
The data was split into training and testing sets.

2. Model Training
Logistic Regression
A logistic regression model was instantiated and trained using the training data.

3. Model Evaluation
Predictions
Predictions were made on the testing data.
Performance Metrics
The model's performance was evaluated using a confusion matrix and a classification report.

Confusion Matrix:
The model correctly identified 14,926 healthy loans and 461 high-risk loans.
The model had 75 false positives (incorrectly classified healthy loans) and 46 false negatives (incorrectly classified high-risk loans).

Classification Report:
Precision, recall, and F1-score were calculated for both healthy and high-risk loans.
The model achieved an overall accuracy of 99%.

4. Analysis Summary
The logistic regression model performed exceptionally well, with an overall accuracy of 99%. It demonstrated perfect performance in predicting healthy loans and strong performance in identifying high-risk loans. This model is recommended for evaluating loan applications due to its high accuracy and reliability.

Extra Tools Used
ChatGPT was utilized to assist with debugging, optimizing code functionality, evaluating the model's performance using confusion matrix and classification report, and summarizing the report.

Reference
OpenAI. (n.d.). ChatGPT by OpenAI from https://openai.com/chatgpt
