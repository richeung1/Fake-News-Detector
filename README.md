# Fake-News-Detector

This is a fake news detector, using multiple Machine Learning models (Logistic Regression, KNNeighbors, and Random Forest). 

I am using a popular Fake vs. Real News dataset from Kaggle (https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset).

I have combined the Fake.csv and True.csv into one file named news_articles.csv.

As of 4/26/2022 the accuracy is ~80% after using GridSearchCV on K-Nearest Neighbors.

There will be more improvements to come such as testing GridSearchCV on different models and creating visuals (heatmaps, confusion matrix, etc.).

Later on I will be using Transformers to see if there are improvements in accuracy.
