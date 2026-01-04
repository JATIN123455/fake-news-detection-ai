# Fake News Detection using NLP and Machine Learning

## Overview
This project implements a fake news detection system using natural language processing techniques and machine learning models. The objective is to classify news articles as real or fake.

## Dataset
The dataset is sourced from Kaggle (Fake and Real News Dataset). Due to licensing restrictions, the raw dataset is not included in this repository.

## Methods
- Text preprocessing (lowercasing, stopword removal, lemmatization)
- Feature extraction using TF-IDF
- Rule-based baseline classifier
- Machine learning models:
  - Multinomial Naive Bayes
  - Logistic Regression

## Evaluation
Models are evaluated using accuracy, precision, recall, F1-score, and confusion matrix.

## How to Run
1. Upload the dataset to the Colab environment or local machine
2. Open the notebook in `notebooks/`
3. Run all cells sequentially

## Results
Logistic Regression outperformed the rule-based approach and Naive Bayes model.

## Ethical Considerations
This project discusses ethical implications including bias, misinformation impact, and transparency.

