# 📈 Price Prophet

**Price Prophet** is a deep learning-driven stock market prediction system that forecasts short-term price movements based on historical data and technical indicators.

It aims to make stock forecasting more transparent, interactive, and accurate by combining time series modeling, backtesting, and confidence interval visualization.

---

## 🚀 Features

- LSTM-based deep learning model for price forecasting
- Automatic feature engineering (EMA, RSI, MACD, etc.)
- Interactive Streamlit dashboard
- Simulated backtesting to visualize strategy performance
- Modular codebase for easy extension

---

## 📚 Stack

- Python+
- PyTorch
- pandas, numpy, scikit-learn
- yfinance (for stock data)
- ta (technical indicators)
- Streamlit
- Plotly

---

## 📂 Project Structure

```bash
price-prophet/
│
├── data/                  # Data storage
├── notebooks/             # Jupyter notebooks for exploration and prototyping
├── models/                # Model architecture and training scripts
├── utils/                 # Helper functions (data loading, feature engineering)
├── app/                   # Frontend Streamlit app
├── requirements.txt       # Python dependencies
├── .gitignore             # Ignore checkpoints, venvs, etc
└── README.md              # Project overview
