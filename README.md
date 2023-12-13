# DSCI 303 Final Project -- Fraud Credit Card Transaction Detection

## Member

(Apple) Xuanchen Li -- xl102

(Derek) Tiancheng Fu -- tf18

## Dataset

In this project, we decided to use the dataset “Credit Card Transactions Fraud Detection Dataset” found on Kaggle. The dataset is created using a simulator (but should be highly similar to a real-world dataset in credit card transactions) and contains both legitimate and fraudulent credit card transactions from 1/1/2019 to 12/32/2020.

## Problem Statement

Fraud detection has played a crucial part in building secure products for companies that offer financial services. By clearly, efficiently, and accurately identifying fraud transactions, companies are able to prevent clients from losing money. In this project, we aim to train a model that distinguishes between legitimate and fraudulent transactions specifically on credit cards. Such models can be used by banks and online payment companies to block malicious transactions and protect their customers’ properties.

Our hypothesis is that fraudulent credit card transactions are associated with unusual patterns, and can be detected by identifying differences from a cardholder’s normal behavior and transaction characteristics.

## Modeling

We used logistic regression as our baseline model. We also tried support vector machine (SVM), random forest and adaptive boosting.

## Final Report

You may access our final report at `DSCI 303 Final Report/dsci303-final-report.pdf`.

## Python Notebook

Our code can be found in `DSCI_303_Final_Project_Credit_Card_Fraud_Detection.ipynb`. You may also view our code via this link to our Google Colab notebook: https://colab.research.google.com/drive/1Qexf5FSwlXxVvhllHtjL9LykM8vk-oyK?usp=sharing
