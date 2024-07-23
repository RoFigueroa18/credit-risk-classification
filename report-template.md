# Module 12 Report Template

Analysis Overview
Purpose of the Analysis
The purpose of this analysis is to evaluate the creditworthiness of borrowers using historical lending data from a peer-to-peer lending services company. By building a machine learning model, we aim to predict whether a loan will be healthy or high-risk based on various financial attributes of the borrowers.

Financial Information and Predictions

The dataset includes various financial information such as:
Loan size
Interest rate
Borrower income
Debt-to-income ratio
Number of accounts
Derogatory marks
Total debt

The target variable is loan_status, where:

0 indicates a healthy loan
1 indicates a high-risk loan
Machine Learning Process
Data Preprocessing
Load the Data: The data from lending_data.csv is read into a Pandas DataFrame.
Create Labels and Features:
The target variable (y) is separated from the feature variables (X).
Split the Data: The data is split into training and testing sets using train_test_split.
Model Training
Logistic Regression: Using LogisticRegression from sklearn, a model is built and trained with the training data.
Model Evaluation
Predictions: Predictions are made using the testing data.
Performance Metrics: The model's performance is evaluated using accuracy, confusion matrix, and classification report.
Results
Machine Learning Model: Logistic Regression
Accuracy: 0.99
Precision:
Healthy Loan (0): 1.00
High-Risk Loan (1): 0.86
Recall:
Healthy Loan (0): 1.00
High-Risk Loan (1): 0.91
F1-Score:
Healthy Loan (0): 1.00
High-Risk Loan (1): 0.88

Summary and Recommendation
The logistic regression model performs exceptionally well in predicting healthy loans, achieving perfect scores in precision, recall, and F1-score. It also shows strong performance in predicting high-risk loans, with a precision of 0.86 and a recall of 0.91. Given the high overall accuracy of 99%, the model is highly reliable for predicting loan statuses.

Key Insight: If the priority is to avoid high-risk loans, the model's recall for high-risk loans (0.91) is crucial.
Recommendation: I recommend using this logistic regression model for evaluating loan applications due to its high overall accuracy and strong performance in identifying both healthy and high-risk loans.

