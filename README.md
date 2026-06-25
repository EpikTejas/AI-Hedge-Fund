# AI-Hedge-Fund
AI-powered cryptocurrency trading dashboard built with FastAPI and Streamlit. Uses RSI and Moving Average analysis to generate BUY, HOLD, and SELL signals from live Binance market data.

# 📈 AI Hedge Fund

An AI-powered cryptocurrency trading dashboard built with **FastAPI** and **Streamlit** that analyzes live Binance market data using technical indicators to generate BUY, HOLD, and SELL trading signals.

---

## Dashboard

![Dashboard](screenshots/dashboard.png)

---

## Features

- 📊 Live cryptocurrency prices from Binance
- 📈 Interactive candlestick charts
- 📉 RSI (Relative Strength Index)
- 📊 Moving Average (MA20)
- 📦 Volume Spike Detection
- ⚡ Volatility Analysis
- 🤖 BUY / HOLD / SELL signal generation
- 🎯 Confidence Score
- 🌙 Dark Mode Dashboard
- 🔄 Auto-refresh every 100 seconds

---

## Tech Stack

- Python
- FastAPI
- Streamlit
- Plotly
- Pandas
- Requests
- Binance API

---

## Project Structure

```
AI-Hedge-Fund
│
├── backend
│   └── main.py
│
├── frontend
│   └── app.py
│
├── screenshots
│   └── dashboard.png
│
├── requirements.txt
├── README.md
├── LICENSE
└── .gitignore
```

---

## Installation

Clone the repository

```bash
git clone https://github.com/EpikTejas/AI-Hedge-Fund.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Start the backend

```bash
cd backend
python -m uvicorn main:app --reload
```

Open another terminal

```bash
cd frontend
python -m streamlit run app.py
```

Open your browser

```
http://localhost:8501
```

---

## Supported Assets

- Bitcoin (BTCUSDT)
- Ethereum (ETHUSDT)
- Solana (SOLUSDT)

---

## Future Improvements

- AI News Sentiment Analysis
- Portfolio Tracking
- Risk Management
- Multi-Agent AI Hedge Fund
- Local LLM Integration
- Trade History
- Additional Technical Indicators

---

## License

This project is licensed under the MIT License.
