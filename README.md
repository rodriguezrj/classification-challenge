# classification-challenge
Module 13

# Classification Challenge: Spam Email Detection

This repository contains code for a classification challenge aimed at detecting spam emails. The challenge involves:

- Splitting the dataset into training and testing sets.
- Scaling the features.
- Training a Logistic Regression model.
- Training a Random Forest Classifier model.
- Evaluating the models.

## Dataset

The dataset used in this challenge can be accessed from the following link:

[Spam Email Dataset](https://static.bc-edx.com/ai/ail-v-1-0/m13/challenge/spam-data.csv)

The dataset contains features extracted from emails, such as word frequencies and character frequencies, along with a target variable indicating whether an email is spam or not.

## Implementation

spam_detector.ipynb: Jupyter Notebook containing the implementation of the classification challenge.
README.md: This README file providing an overview of the challenge and its implementation.

## Results
After implementing the models and evaluating their performance, we found that the Random Forest Classifier model performed slightly better than the Logistic Regression model in predicting whether emails are spam or not. Both models achieved high accuracy scores, indicating their effectiveness in classifying spam emails.