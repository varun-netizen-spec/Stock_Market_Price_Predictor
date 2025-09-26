📈 Stock Market Price Predictor

This project demonstrates stock price prediction using Machine Learning in Python.
We use Tesla stock data (2010–2017) and apply ML models to predict whether buying a stock on a given day will be profitable (binary classification).

🚀 Features

Exploratory Data Analysis (EDA) with visualization 📊

Feature Engineering (technical & time-based features) ⚙️

Data preprocessing & normalization 🔄

ML Models:

Logistic Regression

Support Vector Machine (SVM)

XGBoost Classifier

Evaluation using ROC-AUC score & Confusion Matrix ✅

📂 Dataset

Dataset: Tesla Stock Price Data (2010–2017)

Source: Yahoo Finance / Kaggle

Features used:

OHLC (Open, High, Low, Close)

Volume

Engineered features: open-close, low-high, is_quarter_end, day, month, year

🛠️ Installation

Clone the repo:

git clone https://github.com/your-username/stock-market-price-predictor.git
cd stock-market-price-predictor


Install dependencies:

pip install -r requirements.txt

📒 Usage

Run the Jupyter Notebook:

jupyter notebook Stock_Market_Price_Predictor.ipynb


Or execute the script version (if provided):

python stock_predictor.py

📊 Results

Logistic Regression → Validation AUC ≈ 0.54

SVM (poly kernel) → Validation AUC ≈ 0.44

XGBoost → Validation AUC ≈ 0.57 (but overfitting observed)

📌 Conclusion: Predicting stock prices with simple ML models is challenging due to market noise and limited features.
Future work can include:

Using technical indicators (RSI, MACD, Moving Averages).

Training deep learning models (LSTM/GRU) for time series.

Expanding dataset for better generalization.
