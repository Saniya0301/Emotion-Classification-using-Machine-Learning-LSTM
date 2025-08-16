# Emotion Classification using Machine Learning & LSTM

This project classifies human emotions from text using both **traditional ML models** (Logistic Regression, Naive Bayes, Random Forest, SVM) and **Deep Learning (LSTM)**.

The dataset contains text comments labeled with emotions like *joy, sadness, anger, love, fear, surprise*.

---

## 📌 Features
- Data preprocessing (cleaning, stopwords removal, stemming)
- Exploratory Data Analysis (EDA) with **Seaborn** & **WordClouds**
- Machine Learning models with **TF-IDF features**
- Deep Learning with **Keras LSTM model**
- Model persistence using **pickle** (`.pkl`) and `.h5` formats
- Predict emotions for **custom sentences**

---
📊 Data Preprocessing

Remove special characters, numbers, and punctuation

Convert text to lowercase

Remove stopwords

Apply Porter Stemming

Encode labels using LabelEncoder

Split dataset into train/test sets

---

🤖 Machine Learning Models

Trained using TF-IDF features:

Multinomial Naive Bayes

Logistic Regression

Random Forest

Support Vector Machine (SVM)

✅ Best accuracy was achieved with Random Forest (~85%).


---
Author

SANIYA CHHABRA
