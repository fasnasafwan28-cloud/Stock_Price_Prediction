# 📈 Stock Price Prediction Web Application

## 🚀 Overview

This project is a Flask-based web application that predicts stock prices using a Deep Learning **LSTM (Long Short-Term Memory)** model. The application fetches historical stock market data, performs technical analysis, and visualizes stock price predictions through interactive charts.

---

## ✨ Features

✅ Stock Price Prediction using LSTM Neural Networks  
✅ Historical Data Fetching with Yahoo Finance  
✅ Technical Analysis with Exponential Moving Averages (EMA)  
✅ Interactive Data Visualization  
✅ Download Historical Dataset as CSV  
✅ Flask-Based User Interface  
✅ Real-Time Stock Symbol Input

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|----------|
| 🐍 Python | Programming Language |
| 🌐 Flask | Web Framework |
| 🤖 TensorFlow / Keras | Deep Learning Model |
| 🐼 Pandas | Data Processing |
| 🔢 NumPy | Numerical Computing |
| 📊 Matplotlib | Data Visualization |
| ⚙️ Scikit-Learn | Data Scaling |
| 💹 Yahoo Finance (yfinance) | Stock Market Data |

---

## 📂 Project Structure

```text
stockpriceprediction/
│
├── app.py
├── Price Predictions Model.h5
├── PowerGrid.xls
│
├── static/
│   ├── ema_20_50.png
│   ├── ema_100_200.png
│   └── Stock_Prediction.png
│
├── templates/
│   └── index.html
│
└── README.md
```





---

## 🔄 Workflow

### 1️⃣ User Inputs Stock Symbol

Example:

```text
POWERGRID.NS
```

### 2️⃣ Historical Stock Data Downloaded 📥

Data is fetched using Yahoo Finance.

### 3️⃣ Data Preprocessing ⚙️

- Data Cleaning
- Feature Scaling
- Sequence Generation

### 4️⃣ Model Prediction 🤖

The trained LSTM model predicts future stock trends.

### 5️⃣ Technical Analysis 📊

The application calculates:

- EMA 20
- EMA 50
- EMA 100
- EMA 200

### 6️⃣ Visualization 📈

Generated Charts:

📌 Closing Price vs EMA 20 & EMA 50

📌 Closing Price vs EMA 100 & EMA 200

📌 Actual Price vs Predicted Price

### 7️⃣ Dataset Export 📄

Users can download stock data as CSV.

---





## 📸 Application Screenshots

### 🏠 Home Page
home_page.png

### 📊 EMA Analysis Dashboard
ema_analysis.png

### 📈 Stock Prediction Chart
stock_prediction.png

### 📥 Dataset Download Feature
dataset_download.png


---


## 👨‍💻 Author

**Fasna Safvan**

Aspiring Data Scientist | Machine Learning Enthusiast | Data Analytics Learner

---

## ⭐ Support

If you found this project useful:

🌟 Star this repository

🍴 Fork this repository

📢 Share with others

---
