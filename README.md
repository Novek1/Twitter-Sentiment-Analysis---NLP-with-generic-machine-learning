# X-Sentiment-Analysis---NLP-with-generic-machine-learning
Analyze the sentiment of posts from X (formerly Twitter) using classic machine learning techniques. This project demonstrates a full NLP pipeline with feature extraction, model training, and evaluation.
![Twitter Logo](https://upload.wikimedia.org/wikipedia/commons/b/b7/X_logo.jpg)
---

## Table of Contents

- [Overview](#overview)  
- [Features](#features)  
- [Dataset](#dataset)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Machine Learning Models](#machine-learning-models)  
- [Results](#results)  
- [Contributing](#contributing)  
- [License](#license)  

---

## Overview

This project aims to classify X posts (tweets) into **positive**, **negative**, and **neutral** sentiments using generic machine learning models. It focuses on:

- Text preprocessing (cleaning, tokenization, vectorization)  
- Feature extraction using `TfidfVectorizer`  
- Training multiple ML classifiers  
- Evaluating model performance  
- Building a reproducible NLP pipeline  

---

## Features

- Preprocess raw X posts  
- Transform text into TF-IDF vectors  
- Train and evaluate multiple models:
  - Naive Bayes  
  - K-Nearest Neighbors (KNN)  
  - Support Vector Classifier (SVC)  
- Compare model performance  
- Easy-to-use pipeline for new data  

---

## Dataset
[Twitter Sentiment Analysis on Kaggle ](https://www.kaggle.com/datasets/jp797498e/twitter-entity-sentiment-analysis#:~:text=more_vert-,Twitter%20Sentiment%20Analysis,-Entity%2Dlevel%20sentiment)  
- The dataset consists of X posts with labels for sentiment (positive, negative, neutral).  
- Can be replaced with your own scraped or downloaded X dataset.  
- Sample preprocessing includes: removing URLs, mentions, hashtags, and special characters.  

---

## Installation

1. Clone the repository:

```bash
git clone https://github.com/Novek1/X-Sentiment-Analysis---NLP-with-generic-machine-learning.git
cd X-Sentiment-Analysis---NLP-with-generic-machine-learning
