# 📈 Cryptocurrency Price Forecasting using LSTM

This project predicts the price of cryptocurrencies (BTC, ETH, SOL) using an LSTM (Long Short-Term Memory) neural network. The interactive interface is built with Streamlit, and real-time historical data is fetched directly from the Binance API.

---

## 🔧 Features

- Choose from cryptocurrencies: **BTC**, **ETH**, **SOL**
- Select forecasting period: **1 day**, **1 week**, or **1 month**
- Visual forecast plot with historical and predicted prices
- Real-time data pulled from Binance

---

## 📦 Technologies

- Python 3.10+
- TensorFlow / Keras
- Pandas / NumPy
- Streamlit
- Binance API
- Matplotlib

---

## 📥 Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/crypto-lstm-forecast.git
cd crypto-lstm-forecast
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the Streamlit app:
```bash
streamlit run app.py
```

---

## 📊 Screenshots

| Main Interface | Forecast Graph |
|----------------|----------------|
| ![main](screenshots/main.png) | ![forecast](screenshots/forecast.png) |

> *(Place your screenshots in the `screenshots/` folder and update the paths above)*

---

## 📁 Project Structure

```
crypto-lstm-forecast/
├── app.py              # Streamlit interface
├── data_loader.py      # Fetches and preprocesses data from Binance
├── lstm_model.py       # Builds and runs the LSTM model
├── utils.py            # Graphs and helper functions
├── requirements.txt    # Python dependencies
├── README.md           # Project documentation
└── screenshots/        # UI screenshots (optional)
```

---

## 🧠 Author

**[Your Name]**  
Course project for *Machine Learning / Data Analysis / Intelligent Systems*  
Year: 2025

---

## 📜 License

This project is for educational purposes only and is not licensed. You are free to use or adapt it with proper credit.
