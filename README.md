# Credit-card-fraud-detection-using-all-classification-algorithm
title: Credit Card Fraud Detection

Problem Statement: The challenge in credit card fraud detection is the class imbalance. In a typical scenario, out of 100 transactions, only 5 might be fraudulent. This imbalance can cause a model to be biased towards the majority class, making it less effective at identifying fraudulent transactions.

Solution Approach:

Sampling Technique: To address the class imbalance, I implemented a sampling technique.  oversampling the minority class (fraudulent transactions), is used. This helps to ensure that the model is not biased and can accurately identify both fraudulent and legitimate transactions.
Exploratory Data Analysis (EDA): conducted EDA on the data to understand the underlying patterns and trends. This involves visualizing the data, calculating summary statistics, and identifying any correlations.
Model Selection:Trained several classification algorithms on the data, including Decision Tree, K-Nearest Neighbors (KNN), and Logistic Regression. Each of these algorithms has its own strengths and weaknesses, and they can often perform differently depending on the specific characteristics of the data.
Model Evaluation: After training the models,  evaluated their performance. The Logistic Regression model achieved the highest accuracy of 96%, making it the best algorithm for this particular problem statement.
