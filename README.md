# 🐦 Twitter Sentiment Analysis

### 📊 **Project Overview**

This project performs sentiment analysis on Twitter data using Natural Language Processing (NLP) and Machine Learning techniques. The primary objective is to build a model capable of classifying tweets as positive, negative, or neutral based on their textual content.

#### 💬 **What is Sentiment Analysis?**

Sentiment analysis, also known as opinion mining, is the computational process of identifying and categorizing opinions expressed in text to determine the writer’s attitude toward a particular topic. It plays a vital role in understanding public opinion, emotional tone, and social trends across large volumes of unstructured text data.

#### ❓ Why Sentiment Analysis?

Business: Helps companies understand customer opinions, assess marketing effectiveness, and improve products and services.

Politics: Tracks public opinion on leaders and policies, and supports election prediction efforts.

Social Monitoring: Gauges public mood, detects emerging social issues, and aids in research and policy development.

By applying NLP techniques and training a machine learning model on labeled Twitter data, this project demonstrates how sentiment analysis can extract meaningful insights from social media content.

### 🔁 Project Steps

### 1️⃣ Exploratory Data Analysis (EDA)

Loaded and explored a dataset containing 1.6 million tweets across 6 columns.

Verified there were no missing values, though the first row was mistakenly interpreted as column headers.

Noted the need for cleaning the tweet text, as it included stopwords, punctuation, and noise.

Observed that the target column was evenly distributed, ensuring a balanced dataset.

Confirmed the need to convert text into numerical format for model compatibility.

### 2️⃣ Data Cleaning

Performed the following preprocessing steps:

Replaced incorrect column headers with appropriate names.

Verified sentiment labels:

0 → Negative tweet

1 → Positive tweet

Cleaned the tweet text by:

Lowercasing

Removing URLs, mentions, hashtags, numbers, and punctuation

Removing stopwords

Stored the cleaned text in a new column named clean_text.

### 3️⃣ Model Building and Evaluation

Split the dataset into training and testing sets.

Converted cleaned text into numerical format using feature extraction techniques (e.g., TF-IDF).

Trained a Logistic Regression model on the training data.

#### 🔍 Evaluation Metric:

Accuracy Score: Measures the ratio of correctly predicted tweets to the total number of predictions.

### 4️⃣ Final Model Evaluation

The model achieved an accuracy of 78.38% on training data, indicating effective learning.

On the test data, the model achieved 77.93% accuracy, demonstrating strong generalization and reliable sentiment prediction.

### ✅ Conclusion

This project successfully developed a sentiment analysis model for classifying tweets using machine learning techniques. With a focus on text preprocessing and feature extraction, the Logistic Regression model delivered consistent and reliable performance — achieving 78.38% accuracy on training data and 77.93% on test data.

These results highlight the model's effectiveness in interpreting the emotional tone of tweets, making it a valuable tool for analyzing public opinion, brand perception, and social media trends.











