# 📈 StockVision: LSTM-Based Stock Price Prediction Dashboard

**StockVision** is an AI-powered interactive dashboard that predicts and visualizes future stock prices for multiple NSE-listed companies using **LSTM (Long Short-Term Memory)** neural networks and **Yahoo Finance** data.

---

## 🚀 Features
- Multi-company selection (Tata Steel, Reliance, Infosys, HDFC Bank, etc.)
- Streamlit-based interactive UI with dropdowns and sliders
- Historical price visualization with moving averages
- Daily returns and volatility analysis
- LSTM deep learning model for stock forecasting
- 10–30 day future price predictions with charts
- RMSE & MAE performance metrics
- Option to export predictions as CSV

---

## 🧩 Tech Stack
**Python**, **TensorFlow/Keras**, **Streamlit**, **Yahoo Finance API**, **Matplotlib**, **Seaborn**, **Scikit-learn**

---

## ⚙️ Setup & Run

### 1️⃣ Clone & Enter Folder
bash
git clone https://github.com/<your-username>/StockVision.git
cd StockVision
### 2️⃣ Create Virtual Environment
python3 -m venv venv
source venv/bin/activate
### 3️⃣ Install Requirements
pip install -r requirements.txt
### 4️⃣ Run the App
streamlit run stock_app.py

Then open 👉 http://localhost:8501
