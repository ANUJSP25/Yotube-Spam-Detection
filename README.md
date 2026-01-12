# YouTube Spam Detection using Machine Learning

## Overview
This project focuses on detecting spam comments on YouTube using classical machine learning techniques. The goal is to automatically classify user comments as **spam** or **ham (non-spam)** to help moderate harmful or promotional content on social media platforms.

The system uses text preprocessing, feature extraction, and a **Naive Bayes classifier** to achieve high accuracy on labeled comment data.

---

## Problem Statement
YouTube comment sections are often targeted by spam messages promoting scams, fake giveaways, or malicious links. Manual moderation is time-consuming and error-prone.  
This project demonstrates how machine learning can be used to **automatically identify spam content** based on textual patterns.

---

## Approach
1. **Data Collection**
   - Labeled YouTube comment dataset containing spam and non-spam comments

2. **Text Preprocessing**
   - Lowercasing
   - Tokenization
   - Stopword removal
   - Punctuation and noise removal

3. **Feature Extraction**
   - Bag of Words (BoW) / TF-IDF vectorization

4. **Model Training**
   - Naive Bayes classifier for probabilistic text classification

5. **Evaluation**
   - Accuracy, precision, recall, and confusion matrix

---

## Results
- Achieved **~95% classification accuracy** on the test dataset
- Model successfully identifies promotional and malicious spam patterns
- Demonstrates strong performance for a lightweight, interpretable ML approach

---

## Technologies Used
- **Python**
- **scikit-learn**
- **Pandas, NumPy**
- **NLTK** for text preprocessing
- **Matplotlib / Seaborn** for evaluation and visualization
