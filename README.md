# Fake News Detection Project




The project aims to develop a machine-learning model capable of identifying and classifying any news article as fake or not. The distribution of fake news can potentially have highly adverse effects on people and culture. This project involves building and training a model to classify news as fake news or not using a diverse dataset of news articles. We have used four techniques to determine the results of the model.

1. **Logistic Regression**
2. **SVM**
3. **KNN**
4. **Random Forest Classifier**

## Project Overview

Fake news has become a significant issue in today's digital age, where information spreads rapidly through various online platforms. This project leverages machine learning algorithms to automatically determine the authenticity of news articles, providing a valuable tool to combat misinformation.

## Dataset

We have used a labelled dataset containing news articles along with their corresponding labels (true or false). The dataset is divided into two classes:
- True: Genuine news articles
- False: Fake or fabricated news articles

*Dataset Link(you can copy and paste the link )*

import kagglehub

path = kagglehub.dataset_download("secondbenchbuddies/true-and-fake-dataset")

print("Path to dataset files:", path)


## Dependencies

Before running the code, make sure you have the following libraries and packages installed:

- Python 3
- Scikit-learn
- Pandas
- Numpy
- Seaborn
- Matplotlib
- Regular Expression

## Methodology
Data Collection ( True-FakeCSV dataset)
Data Preprocessing (cleaning, removing stopwords)
Feature Extraction (TF-IDF )
Model Training
Evaluation (Accuracy, Precision, Recall, F1-score)


The code will produce evaluation metrics and provide a prediction for whether the given news is true or false based on the trained model.

## Results

We evaluated each classifier's performance using metrics such as accuracy, precision, recall, and F1 score. The results are documented in the project files.

## Model Deployment

Once you are satisfied with the performance of a particular classifier, you can deploy it in a real-world application or integrate it into a larger system for automatic fake news detection.
---


import kagglehub

# Download latest version
path = kagglehub.dataset_download("secondbenchbuddies/true-and-fake-dataset")

print("Path to dataset files:", path)
