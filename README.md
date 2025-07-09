# 📈 Stock Sentiment Analysis Using LSTM

This project explores the relationship between financial news sentiment and stock price movement using machine learning.

## 🧠 Problem Statement

Can we use financial news sentiment to predict short-term stock movement?  
We explore this question using data from **NewsAPI** (news headlines) and **Yahoo Finance** (stock data for HDFC Bank).

## 📦 Tools & Libraries

- `pandas`, `numpy`, `yfinance`, `newsapi-python`
- `TextBlob` for sentiment analysis
- `scikit-learn` for ML models
- `tensorflow.keras` for LSTM model

## 📊 Models Implemented

| Model              | Accuracy |
|-------------------|----------|
| Logistic Regression | 60%      |
| SVM (RBF)          | 80%      |
| LSTM (win=3)       | 80%      |
| LSTM (win=5)       | 80%      |

## 📌 Results

LSTM and SVM both outperformed traditional models, showing that **news sentiment** can be a powerful signal in stock prediction.

## 🔚 Conclusion

This project demonstrates the potential of using sentiment analysis in trading. Future improvements may include:
- Using live news feeds
- More sophisticated NLP models (like BERT)
- More historical and intraday stock data
