
# 🔐 Phishing Detection System

This project detects phishing websites and emails using Machine Learning.


## 🚀 Features

* Detects fake websites (URL)
* Detects phishing emails (text)
* Shows result with confidence score
* Explains prediction using LIME
* Chrome extension for real-time checking

## 🛠️ Tech Used

* Python
* FastAPI
* XGBoost
* TF-IDF
* LIME
* HTML, CSS, JavaScript

## ⚙️ How it works

1. Enter URL or email text
2. Convert data using TF-IDF
3. Model predicts Safe or Phishing
4. Shows result + explanation

## ▶️ Run Project

```bash
pip install -r requirements.txt
uvicorn main:app --reload

## 🌐 Chrome Extension

* Checks current website
* Alerts if phishing detected

## 📌 Future Work

* Improve accuracy
* Add deep learning
* Deploy online
