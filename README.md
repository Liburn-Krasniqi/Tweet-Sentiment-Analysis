# Tweet Sentiment Analysis with SVM

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![scikit-learn](https://img.shields.io/badge/scikit--learn-1.0%2B-orange)
![NLTK](https://img.shields.io/badge/NLTK-3.6%2B-green)
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/LiburnKrasniqi/Project-B---ICT-AI-v3.ipynb/blob/main/sentiment_analysis.ipynb)

## Overview

This project implements a **sentiment analysis model** to classify tweets as positive or negative using a **Support Vector Machine (SVM)**. The dataset consists of 10,000 tweets (5,000 positive, 5,000 negative), and the model achieves an impressive **98.8% accuracy** on the test set. 
The key innovation is a custom preprocessing pipeline that leverages **emoticons** (e.g., `:)` → "smile", `:(` → "frown", `<3` → "heart") to capture strong sentiment signals, significantly boosting performance from an initial 74% to 94% and finally to 98.8%.

This project was developed as part of a school assignment, with a focus on building a custom model without pre-trained embeddings or deep learning frameworks.

## Features

- **Dataset**: 10,000 balanced tweets (50% positive, 50% negative).
- **Model**: Linear SVM with TF-IDF features and custom emoticon handling.
- **Preprocessing**: Custom pipeline including emoticon mapping, emoji processing, lemmatization, and stop word removal.
- **Accuracy**: 98.8% on a 30% test split (3,000 tweets), improved from 74% through iterative feature engineering.
- **Key Innovation**: Mapping emoticons (e.g., `:)` to "smile") as tokens, capturing critical sentiment cues.

## Methodology

Dataset
Size: 10,000 tweets (5,000 positive, 5,000 negative).

Split: 70% train (7,000), 30% test (3,000).

Source: [https://www.nltk.org/api/nltk.corpus.html](https://www.nltk.org/api/nltk.corpus.html)

## Author
Liburn Krasniqi
