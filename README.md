# btc-price-prediction-streamlit
A Streamlit-based machine learning web app to predict Bitcoin (BTC) closing price using cryptocurrency market indicators like USDT and BNB prices and volumes.
# 📈 BTC Close Price Prediction App

A machine learning–powered **Streamlit web application** that predicts the **Bitcoin (BTC) closing price** using key cryptocurrency market indicators such as **USDT price, USDT volume, BNB price, and BNB volume**.

This project demonstrates the end-to-end workflow of **data preprocessing, model training, and deployment** using Python and Streamlit.

---

## 🚀 Features

- Interactive Streamlit dashboard
- User-friendly sidebar input controls
- Real-time BTC price prediction
- Trained machine learning regression model
- Clean and minimal UI design
- Easy to deploy and extend

---

## 🧠 Machine Learning Model

- **Type:** Regression Model  
- **Inputs:**
  - USDT Close Price
  - USDT Volume
  - BNB Close Price
  - BNB Volume
- **Output:**
  - Predicted BTC Close Price

The model is trained on historical cryptocurrency market data and saved using `pickle` for deployment.

---

## 🛠️ Tech Stack

- **Python**
- **Pandas & NumPy**
- **Scikit-learn**
- **Streamlit**
- **Matplotlib (optional visualization)**
- **Pickle**

---

## 📂 Project Structure

```bash
btc-price-prediction-streamlit/
│
├── app.py                 # Streamlit frontend application
├── btc_model.pkl          # Trained ML model
├── scaler.pkl             # Feature scaler
├── README.md              # Project documentation
└── data/                  # Dataset
📊 Application Preview

The dashboard allows users to adjust crypto market values using sidebar inputs and instantly predicts the BTC closing price.

🎯 Learning Outcomes

Building ML-powered web applications

Model serialization using Pickle

Feature scaling and prediction pipelines

Streamlit UI & deployment fundamentals

End-to-end ML project workflow

🔮 Future Improvements

Add live crypto price API integration

Include time-series models (LSTM, ARIMA)

Display confidence intervals

Improve feature engineering

Deploy on Streamlit Cloud / Render

📌 Author
Haimabati Haripriya Sahu
Aspiring Data Scientist | Python | Machine Learning | Data Analysis

🔗 Feel free to connect on LinkedIn and explore more projects!
LinkedIn:https://www.linkedin.com/in/haimabati-haripriya-sahu-2a3a1619b/
