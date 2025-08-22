# 📈 Stock Return Prediction with News Sentiment

This project explores whether incorporating **news sentiment** can improve the prediction of next-day stock returns for major technology companies in the NASDAQ.  

We combine:
- Historical price data (OHLCV).
- Market news headlines (sentiment analysis with VADER).
- Feature engineering from both structured (prices, volumes, technical indicators) and unstructured data (text).

The workflow covers **EDA → Feature Engineering → Model Development → Trading Strategy Backtest → Reporting**.

---

## 🗂 Project Structure

```text
.
├── data/                #  Raw price & news data 
├── graphs/              # All figures generated during analysis
│   ├── n_records.png
│   ├── correlations.png
│   ├── distributions.png
│   ├── ...
│
├── notebooks/
│   ├── eda.ipynb        # Exploratory Data Analysis
│   ├── feature.ipynb    # Feature engineering (price + 
│   ├── model.ipynb   # Model development, 
│
├── report/
│   ├── project_report.pdf   # Full academic-style
│   ├── slides.pdf           # 5-slide presentation
│
├── .gitignore
├── LICENSE
└── README.md
