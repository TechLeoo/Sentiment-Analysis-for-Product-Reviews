# Sentiment Analysis on Amazon Product Reviews

## Overview

This project applies Natural Language Processing (NLP) techniques to analyze and classify customer sentiments in Amazon product reviews. By predicting whether a review expresses a positive or negative sentiment, the model enables businesses to better understand customer feedback and inform product development and marketing strategies.

## Objectives

- Classify Amazon product reviews into positive or negative sentiment.
- Preprocess and clean raw text data for NLP tasks.
- Train and evaluate multiple machine learning models on sentiment-labeled reviews.
- Visualize insights such as sentiment distribution and common keywords.

## Dataset

- **Source:** Amazon product reviews dataset.
- **Features:**
  - `reviewText`: Full text of the review.
  - `overall`: Numerical rating (used to derive sentiment).
  - `summary`: Short title of the review.
- **Target Variable:** Sentiment label (positive or negative) based on review score.

## Tools & Technologies

- **Python**
- **pandas**, **NumPy** – Data manipulation
- **NLTK**, **spaCy** – Text preprocessing
- **scikit-learn**, **Logistic Regression**, **Naive Bayes**, **SVM** – Modeling
- **TF-IDF**, **CountVectorizer** – Feature extraction
- **Matplotlib**, **Seaborn**, **WordCloud** – Visualization
- **Jupyter Notebook** – Interactive analysis
