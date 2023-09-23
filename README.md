# Credit_card_fraud_detection
Credit_card_fraud detection using machine learning model





OVERVIEW:
This repository contains code and resources for fraud Detection using ML model . It is important that credit card companines able to recognize fraud transcations so that customers are not charged for items that they did not purchase.


CONTENT:

This dataset contains credit card transactions made by European cardholders in the year 2023. It comprises over 550,000 records, and the data has been anonymized to protect the cardholders' identities. The primary objective of this dataset is to facilitate the development of fraud detection algorithms and models to identify potentially fraudulent transactions.
Data Source: - It contains only numerical input variables .  The dataset was collected from credit card transactions made by European cardholders in 2023, with sensitive information removed to ensure privacy and compliance with ethical guidelines. As it's confidentially issues , we cannot provide original features and more information.
In this data Feature 'Class' is the response variable and it takes value 1 in case of fraudulent and 0 for Legit transcation.


DataSource : https://www.kaggle.com/datasets/nelgiriyewithana/credit-card-fraud-detection-dataset-2023
Download the dataset from this link.


INSPIRATION:

Identify fraudulent credit card transactions.
Given class ratio is 50:50  it's quite balance ratio , i meansure the accuracy  with accuracy matrix and classification_report from library sklear_metrics.


OBSERVATIONS:

- Logistic Regression has a 79% accurate , whereas Decision Tree has a 99% accurate
- Here Decision tree performs better as it is 20% more accuracy shown. 
- We can also improve on this accuracy by increasing the sample size or use deep learning algorithms however at the cost of computational expense.We can also use complex anomaly detection models to get better accuracy in determining more fraudulent cases .
- Info: this dataset is not unbalanced so sampling technique is not used , if your dataset is unbalanced we can use any sampling techniques.
  
