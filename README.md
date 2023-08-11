
# Identification Of Disaster Tweets

Natural language processing (NLP) model to classify whether a given tweet is related to a disaster or not. The goal is to create a system that can automatically distinguish between tweets that discuss real disasters ( earthquakes, wildfires, floods ) and those that do not.After training the model, it was able to recognize the test data correctly with 95% accuracy.



## Overview

- Data Collection:
    The datasets contains a set of tweets which have been divided into a training and a test set. The training set contains a target column identifying whether the tweet pertains to a real disasteror not.
    https://www.kaggle.com/competitions/nlp-getting-started/data


- Exploratory Data Analysis (EDA):
    It involves visually and statistically exploring our dataset to understand its structure, patterns, relationships, and potential issues.(missing value,balanced,discover trend)
- Data Preprocessing:
    Clean and preprocess the text data. This typically involves tokenization, removing special characters, converting text to lowercase, and removing stopwords.
- Feature extraction:
    Transform the processed text data into numerical features that can be used by ML model Some common techniques for text feature extraction.In this project, we applied BOW and TF-IDF models on train and test datasets.
- Model Selection:
    In this project, we evaluated three models Logistic Regression, Naive Bayes and SVM on two BOW and TF-IDF methods to find out which method works better on our dataset.
- Model Training:
    Finally, according to the obtained results, the BOW method worked better on the dataset, so we trained the models with the vectors obtained from this method.
- Model Evaluation:
    After training, we evaluated the model with test data, and the logistic regression model performed better than other models on this dynasty with 95% accuracy.



## 🔗 Contact

|||
|-|-|
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:m.moeini67@gmail.com) |[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mina-moeini)


