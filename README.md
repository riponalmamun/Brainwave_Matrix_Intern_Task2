# Brainwave_Matrix_Intern_Task2

AI/Machine Learning  intern
Title: CREDIT CARD FRAUD DETECTION
Description: Develop a fraud detection model to identify fraudulent credit card transactions. Use techniques like anomaly detection or supervised
learning with imbalanced data.
This is my first project (Task 2) from my internship at Brainwave Matrix Solutions , where I dived into the exciting realm of Machine Learning. Here's a breakdown of what I accomplished.
I gathered datasets from Kaggle.This process laid the foundation for subsequent analysis.I split the dataset into training and testing subsets and proceeded to train a Logistic Regression model and Random Forest Model.

About Dataset

Context
It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase.

Content
The dataset contains transactions made by credit cards in September 2013 by European cardholders.
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.Given the class imbalance ratio, we recommend measuring the accuracy using the Area Under the Precision-Recall Curve (AUPRC). Confusion matrix accuracy is not meaningful for unbalanced classification.


Dataset : https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
GitHub :https://lnkd.in/dErvcHWS

