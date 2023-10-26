# Movie Review Sentiment Analysis using NLP

## Project Overview
The Film Junky Union, a new edgy community for classic movie enthusiasts, is developing a system for filtering and categorizing movie reviews. The goal is to train a model to automatically detect negative reviews. 
The dataset consists of IMBD movie reviews with polarity labelling to build a model for classifying positive and negative reviews. The model will need to have an F1 score of at least 0.85.

## Technologies
NLP, Text Vectorization, Lemmatization, TF-IDF, Word Embeddings, Regression models (Logistic Regression, Random Forest, XGBoost, Decision Tree)

## Project Conclusions
- Logistic Regression using NLTK for tokenization and lemmatization performed the best in terms of F1 score (0.87).
- When comparing the best models on 'my reviews', the predictions using spaCy are more accurate than those using NLTK even though the models F1/accuracy scores are similar.
- The Logistic Regression models' prediction probabilities show that they are better at correctly identifying the sentiment of the review when compared to RF/XGBoost, and the spaCy LR model was the best at detecting negative reviews.

![image](https://github.com/laceymalarky/TripleTen_projects/assets/97048468/7f1c663f-dc4d-48c6-ab3e-ea1db1daad2c)

## Requirements
Python libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, nltk, spacy

## Data Description:
- `/datasets/imdb_reviews.tsv`
  - `review`: the review text
  - `pos`: the target, '0' for negative and '1' for positive
  - `ds_part`: 'train'/'test' for the train/test part of dataset, correspondingly
