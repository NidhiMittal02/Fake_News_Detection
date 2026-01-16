# Fake_News_Detection

# 📰 Fake News Classification using Machine Learning

## 📌 Project Overview
This project focuses on detecting **fake news articles** using **Natural Language Processing (NLP)** and **Machine Learning** techniques. The model classifies news articles as **Fake** or **Real** based on their textual content.

## 📂 Dataset link(https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)
The dataset consists of two CSV files:
- **True.csv** → Contains real news articles
- **Fake.csv** → Contains fake news articles

Each dataset includes:
- Title
- Text
- Subject
- Date

## ⚙️ Technologies & Libraries Used
- Python
- Pandas & NumPy
- NLTK
- Scikit-learn
- TensorFlow / Keras
- Matplotlib & Seaborn

## 🧹 Data Preprocessing
- Removed null values
- Combined fake and real datasets
- Text cleaning (lowercasing, punctuation removal)
- Tokenization
- Stopword removal
- Vectorization using TF-IDF

## 🤖 Machine Learning Model
- Bidirectional LSTM
- Train-test split
- Model trained on text features
- Evaluated using accuracy and confusion matrix

## 📊 Results
The model successfully classifies news articles with good accuracy, proving that NLP-based text classification is effective for fake news detection.

## 🚀 How to Run the Project
Install dependencies:
```
pip install pandas numpy nltk scikit-learn tensorflow matplotlib seaborn
```

Run the Jupyter Notebook:
```
Fake_News_Classification_.ipynb
```

## 📌 Conclusion
This project demonstrates how machine learning and NLP can be used to combat misinformation by automatically identifying fake news articles.

