# 📈 AI for Market Trend Analysis  

A machine learning project for predicting Indian stock market trends using **LSTM** and **XGBoost**, enriched with **technical indicators** and **sentiment analysis**.  

---

## 🚀 Features  

- ✅ Fetches Indian stock data using **yfinance**  
- 📊 Includes **technical indicators**: RSI, MACD, EMA, Bollinger Bands  
- 🤖 Implements **LSTM** (deep learning) and **XGBoost** (gradient boosting) models  
- 📰 Adds **sentiment analysis** from financial news/tweets *(optional)*  
- 📉 Visualizes **real vs predicted stock prices**  
- ⚡ Built and tested in **Google Colab**  
- 🌐 Ready for deployment via **Streamlit app**  

---

## 🛠️ Tech Stack  

- **Python 3.9+**  
- **Libraries**:  
  - `yfinance`, `pandas`, `numpy` – Data collection & preprocessing  
  - `ta` – Technical indicators  
  - `matplotlib`, `seaborn`, `plotly` – Visualization  
  - `scikit-learn` – Data splitting, scaling, evaluation  
  - `tensorflow/keras` – LSTM model  
  - `xgboost` – Gradient boosting model  
  - `nltk`, `textblob` – Sentiment analysis  
  - `streamlit` – Web app deployment  

---

## 📂 Project Structure  


AI-for-market-trend-analysis/
│── ai_for_market_trend_analysis.ipynb # Main Colab notebook
│── requirements.txt # Dependencies
│── README.md # Project documentation
│── data/ # (Optional) Saved datasets
│── models/ # Trained model files
│── streamlit_app.py # Streamlit web app (future extension)


---

## 🔧 Installation  

Clone the repository:  

```bash
git clone https://github.com/Hariomkumar42/AI-for-market-trend-analysis.git
cd AI-for-market-trend-analysis

Install dependencies:
pip install -r requirements.txt

▶️ Usage

    1. Open the notebook in Colab.

    2. Modify stock ticker:
   ticker = "RELIANCE.NS"

    3. Run the notebook to train LSTM + XGBoost models.

4.View predictions vs actual stock prices.

📊 Results

   1. LSTM captures sequential price patterns.

   2. XGBoost enhances short-term accuracy.

   3. Combined approach improves reliability.

🌟 Future Work

   1. Add Transformer/GRU models

   2. Expand sentiment analysis with live financial news

   3. Deploy interactive Streamlit dashboard

🤝 Contributing

    Contributions are welcome! Fork the repo, create a branch, and submit a PR.

📜 License

    This project is licensed under the MIT License.
  
---

## 📌 2. `requirements.txt`

      ```txt
      numpy
      pandas
      matplotlib
      seaborn
      scikit-learn
      yfinance
      keras
      xgboost
      ta
      nltk
      textblob
      plotly
      streamlit



