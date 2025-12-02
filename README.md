StockGenius: Advanced AI-Powered Stock Prediction System
🤖 Multiple ML Models | 📊 Real-time Dashboard | 📈 Technical Analysis

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![ML](https://img.shields.io/badge/Machine%20Learning-Advanced-orange)
![Streamlit](https://img.shields.io/badge/Dashboard-Streamlit-green)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

**StockGenius** is an advanced forecasting system that combines **machine learning**, **deep learning**, and **technical analysis** to deliver intelligent, data-driven stock predictions—supporting both global giants like **Apple** and **Tesla**, and key **Pakistani equities** like **PSO**, **OGDC**, and **HUBC**.

Built for traders, analysts, and data science enthusiasts, StockGenius turns market noise into actionable insights—all through an intuitive, real-time dashboard.

# 📈 StockGenius - AI Stock Prediction System


**Advanced stock prediction using Machine Learning & Deep Learning algorithms**

## 🚀 Features

- **Real-time Data**: Live stock prices from Yahoo Finance
- **Multiple Models**: XGBoost, LSTM, Prophet, Ensemble methods
- **Technical Analysis**: RSI, MACD, Bollinger Bands, Moving Averages
- **Interactive Dashboard**: Real-time visualization with Streamlit
- **Backtesting**: Historical performance analysis
- **Pakistan Stocks**: PSO, OGDC, HUBC support

## 🛠️ Tech Stack

- **Python 3.9+**
- **Machine Learning**: Scikit-learn, XGBoost, LightGBM
- **Deep Learning**: PyTorch (LSTM models)
- **Visualization**: Plotly, Matplotlib, Seaborn
- **Dashboard**: Streamlit
- **Data**: Yahoo Finance API

## 📁 Project Structure

```bash
StockGenius/
├── data/                 # Raw & processed stock datasets
├── models/               # Saved trained models (.pkl, .pt)
├── notebooks/            # Exploratory data analysis & model prototyping
├── src/                  # Modular source code
│   ├── data_collector.py # Fetches real-time stock data
│   ├── ml_models.py      # Trains & evaluates models
│   ├── visualization.py  # Generates plots & signals
│   └── utils.py          # Helper functions
├── dashboard.py          # Streamlit app entry point
├── requirements.txt      # Project dependencies
└── README.md             # You're here!
```

---

## 🚀 Quick Start

1. **Clone the repo**
   ```bash
   git clone https://github.com/yourusername/StockGenius.git
   cd StockGenius
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Fetch stock data**
   ```bash
   python src/data_collector.py
   ```

4. **Launch the dashboard**
   ```bash
   streamlit run dashboard.py
   ```

> 💡 Make sure you're connected to the internet—live data is pulled from Yahoo Finance.

---

## 📊 Supported Stocks

| Market     | Tickers |
|------------|---------|
| **United States** | `AAPL`, `TSLA`, `GOOGL`, `MSFT`, `AMZN` |
| **Pakistan**      | `PSO.KA`, `OGDC.KA`, `HUBC.KA`, `MCB.KA` |

> 🇵🇰 *Pakistani tickers use the `.KA` suffix for Karachi Stock Exchange on Yahoo Finance.*

---

## 🤖 Models Under the Hood

| Model      | Type          | Use Case |
|------------|---------------|--------|
| **XGBoost** | Ensemble ML   | High-accuracy short-term prediction |
| **LSTM**    | Deep Learning | Captures long-term temporal patterns |
| **Prophet** | Time Series   | Robust trend & seasonality modeling |
| **Ensemble**| Hybrid        | Combines models for superior accuracy |

---

## 📈 Dashboard Highlights

- Live candlestick & line charts  
- Toggleable technical indicators  
- AI-generated **Buy/Sell signals**  
- Prediction confidence intervals  
- Backtesting results with metrics (MAE, RMSE, Accuracy)

---

## 👨‍💻 Author

**Tafseer Haider**  
BSc Computer Science @ University of the People (GPA: 3.85/4.0)  
Aspiring Data Scientist | ML Engineer | Pakistan 🇵🇰  

🔗 [LinkedIn](https://linkedin.com/in/yourprofile) | 📧 your.email@example.com

---

## 📄 License

Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for details.

---

## 🙏 Acknowledgments

- [Yahoo Finance](https://finance.yahoo.com/) – Free, reliable market data  
- [Streamlit](https://streamlit.io/) – For enabling rapid dashboard development  
- The open-source ML community – For libraries that power innovation

---

## 🌐 Live Demo

[![Open in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://stockgenius.streamlit.app/)

> Try it live—no installation required!

---

## 🔗 Recommended GitHub Settings

- **Repository Name**: `StockGenius`  
- **Description**: `AI-powered stock prediction system supporting US & Pakistani markets with ML, deep learning, and real-time dashboard`  
- **Visibility**: Public  
- ✅ Initialize with `README.md`  
- ✅ Add `.gitignore` (Python template)  
- ✅ Add `MIT License`

---

## 🎯 Optional Badges (Add to Top)

```markdown
![GitHub Stars](https://img.shields.io/github/stars/yourusername/StockGenius?style=social)
![GitHub Forks](https://img.shields.io/github/forks/yourusername/StockGenius?style=social)
![Issues](https://img.shields.io/github/issues/yourusername/StockGenius)
![Last Commit](https://img.shields.io/github/last-commit/yourusername/StockGenius)
```
```
