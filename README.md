# YouTube Spam Comment Classification (Naive Bayes)

This project aims to **automatically detect and classify spam comments** on YouTube using the **Multinomial Naive Bayes** algorithm.
This project is part of my learning journey in machine learning.

##  Overview

Spam comments on social media platforms like YouTube are a major concern for both content creators and viewers. This project builds a spam classifier to distinguish between **spam** and **non-spam (ham)** comments machine learning model.

##  Dataset

The dataset used in this project consists of labeled YouTube comments collected from public sources. Each comment is labeled as either:
- `spam`
- `ham` (non-spam)

## Project Workflow


* **Loading and combining datasets**:  Multiple data files are merged to form a unified dataset.
* **Initial data inspection**: Exploratory steps to understand the structure, distribution, and quality of the dataset.
* **Train-test split**: The dataset is split into training and testing subsets to evaluate model generalization.
* **Text vectorization**: Applied `CountVectorizer` to convert raw text into a bag-of-words representation.
* **Model training**: Trained a **Multinomial Naive Bayes** classifier on the training data.
* **Evaluation**: Used confusion matrix and accuracy metrics to assess performance.

## Results

The model performed (90.5%) well in detecting spam comments, with few mistakes. Its accuracy was checked using a confusion matrix and accuracy score
