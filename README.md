# Email-spam-detection
Email Spam Detection using Scikit-learn
This repository contains a Jupyter Notebook (or Google Colab Notebook) that demonstrates building a machine learning model to classify messages as either "ham" (legitimate) or "spam". While the dataset used is SMS messages, the techniques applied are broadly applicable to email spam detection.

The project covers the following key steps:

Data Loading and Preprocessing: Loading the dataset, cleaning the data, converting labels to a numerical format, and splitting the data into training and testing sets.
Text Vectorization: Transforming raw text messages into numerical features using the TF-IDF technique, which quantifies word importance.
Model Training: Training a Multinomial Naive Bayes classifier, a common and efficient model for text classification, on the vectorized training data.
Model Evaluation: Assessing the trained model's performance on unseen testing data using metrics like Accuracy, Precision, Recall, and F1-score to understand its effectiveness.
Using Pipelines: Utilizing scikit-learn pipelines to create a streamlined workflow for vectorization and prediction, which helps prevent data leakage and simplifies deployment.
Making Predictions: Using the trained pipeline to predict whether new messages are spam or ham.
Key Libraries Used:

pandas
scikit-learn
This project serves as a practical example of applying machine learning to a fundamental natural language processing problem – identifying unwanted messages.
