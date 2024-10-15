# CODSOFT_spam_sms
# Project Description
This project aims to build a machine learning model to detect spam SMS messages. Using a dataset provided in the spam.csv file, we explore various natural language processing (NLP) techniques and machine learning algorithms to classify SMS messages as either Spam or Ham (legitimate).

# The spam.csv file contains two main columns:

Message: The SMS text.
Label: Whether the message is labeled as "Spam" or "Ham."
The project involves data preprocessing steps such as text cleaning, tokenization, and feature extraction using methods like TF-IDF. We experiment with multiple classifiers including Naive Bayes, Support Vector Machines (SVM), and Random Forests to determine the best model for this classification task.

# Key Features
Data Preprocessing: Removing punctuation, stop words, and converting text to lowercase for better analysis.
Feature Extraction: Using Term Frequency-Inverse Document Frequency (TF-IDF) to convert SMS text into numerical features.
Model Building: Testing multiple machine learning algorithms to identify the best performing model.
Evaluation Metrics: Assessing model performance using accuracy, precision, recall, and F1-score.
# Conclusion and Outcomes
After applying various machine learning algorithms, the following outcomes were observed:

Naive Bayes performed the best in detecting spam messages, with high accuracy and precision, particularly in correctly identifying spam.
SVM and Random Forests also showed good results but were slightly less efficient in comparison to Naive Bayes.
The feature extraction method (TF-IDF) proved effective in differentiating between spam and legitimate messages, improving model accuracy.
Overall, the project demonstrates how machine learning can be effectively applied to SMS data for spam detection, offering insights into how automated systems can be built to filter out spam messages with high accuracy.
