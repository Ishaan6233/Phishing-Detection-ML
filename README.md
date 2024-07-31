# Phishing Email Detection with Logistic Regression

## Problem Statement
    In the context of email filtering, we aim to develop a model that can accurately classify incoming emails as either "phishing" (spam) or "legitimate" (ham). Phishing emails are malicious attempts to obtain sensitive information such as usernames, passwords, and credit card details by disguising as a trustworthy entity. Detecting phishing emails is crucial for protecting users from fraud and cyber threats. The goal is to build a binary classification model that can predict whether a new, unseen email is a phishing attempt (spam) or a legitimate email (ham).

## Project Overview
### This project utilizes a Logistic Regression model to classify emails as either spam or ham. The dataset used for training and testing the model is preprocessed and includes various steps such as data cleaning, feature extraction, and model evaluation.
The project's pipeline includes:

    Data Preprocessing: Loading and cleaning the dataset, handling missing values, and encoding labels.
    Feature Extraction: Converting text data into numerical data using CountVectorizer.
    Model Training: Training a Logistic Regression model.
    Model Evaluation: Evaluating the model using cross-validation, classification report, ROC curve, and confusion matrix.
    Manual Testing: Providing a function to manually test new email messages.
