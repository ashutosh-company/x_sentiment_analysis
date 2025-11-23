# 📝 Sentiment Analysis on Twitter Data (Sentiment140)

This project performs **Sentiment Analysis** on real Twitter data using the **Sentiment140 dataset**.  
It includes complete preprocessing, feature engineering, model training, and prediction steps to classify tweets as **Positive** or **Negative**.

---

## 🚀 Project Overview

The goal of this project is to build an end-to-end machine learning pipeline that processes raw tweets, cleans the text, converts it into numerical features, and trains a classification model to detect sentiment.

---

## 📌 Key Features

### 🔹 1. Data Collection
- Downloaded the **Sentiment140 dataset** using Kaggle API.  
- Extracted and loaded the dataset for processing.

### 🔹 2. Text Preprocessing
Applied essential NLP preprocessing steps:
- Removal of unnecessary characters  
- Removal of stopwords  
- Tokenization  
- **Stemming** to convert words to their root form  
- Cleaned tweets for consistent feature extraction  

### 🔹 3. Feature Engineering
- Converted textual data into numerical representation using vectorization techniques.
- Prepared clean, structured features for machine learning algorithms.

### 🔹 4. Model Building
- Split data into **training** and **testing** sets.
- Trained an ML classification model to detect **positive** vs **negative** tweets.
- Created predictions for new text inputs.

### 🔹 5. Evaluation
- Evaluated the performance of the model on test data.
- Verified accuracy and prediction quality.

---

## 🔧 Technologies Used
- **Python**
- **Pandas**
- **NumPy**
- **NLTK** (stopwords, stemming)
- **Scikit-learn**
- **Kaggle API**
- **ZipFile** for extraction

---
