# Time Series & Finance

> Starter notebooks for stock-price and crypto-market datasets — clean baselines you can fork and extend, not over-engineered "guaranteed alpha" promises.

Financial time series is a famously hostile domain. The signal-to-noise ratio is low, the data is heteroskedastic, and the "obvious" model is almost always overfit. These notebooks are honest starting points — they show how to load, validate, visualize, and baseline financial datasets, without pretending to predict the future.

---

## 📓 Notebooks in this repo

### 1. Apple Stock 2020–2025 — Starter Notebook 🍎
Five years of AAPL OHLCV data, cleanly loaded and visualized. Rolling means, volatility, return distributions, and a baseline ARIMA / Prophet comparison so you can see why simple models are surprisingly hard to beat on this kind of data.

📔 **[Open on Kaggle →](https://www.kaggle.com/code/samanfatima7/2020-2025-apple-stock-data-starter-notebook)**

---

### 2. Google Stock 2020–2025 — Starter
Same setup, GOOGL data. Useful as a side-by-side comparison with AAPL — different volatility regimes, different sensitivity to broader market moves.

📔 **[Open on Kaggle →](https://www.kaggle.com/code/samanfatima7/2020-2025-google-stocks-starter)**

---

### 3. Microsoft Stock 2020–2025 — Starter
MSFT version. A clean reproducible template for any single-ticker analysis.

📔 **[Open on Kaggle →](https://www.kaggle.com/code/samanfatima7/microsoft-2020-2025-stock-starter-notebook)**

---

### 4. High-Frequency Crypto Market — Starter 🚀
A high-frequency crypto dataset (tick or sub-minute resolution). Time-series at this resolution behaves nothing like daily stock data — you'll see why the rolling statistics that worked above completely break down, and what to use instead.

📔 **[Open on Kaggle →](https://www.kaggle.com/code/samanfatima7/high-frequency-crypto-market-starter)**

---

## 🛠 Stack

Python · pandas · NumPy · Matplotlib · Plotly · statsmodels · Prophet · scikit-learn

## 📂 How this repo is organized

Each notebook is standalone:

```bash
git clone https://github.com/samanfatima7/time-series-and-finance.git
cd time-series-and-finance
pip install -r requirements.txt
jupyter notebook
```

Datasets are public on Kaggle and linked from each notebook.

## 🧭 A warning, in good faith

These are *starters*. They're useful as templates, as teaching material, and as the first step in a more serious analysis. They are **not** trading signals, they are **not** financial advice, and the models in them will lose money if you deploy them as-is. If you're new to this space, the right next step is reading Marcos López de Prado, not running these notebooks against your savings account.

## 👋 About

Saman Fatima — Kaggle Grandmaster, data scientist from Pakistan. More work on [Kaggle](https://www.kaggle.com/samanfatima7) · [LinkedIn](https://www.linkedin.com/in/saman-fatima-datascience/).

⭐ if you found something useful — and reach out if you're doing serious quant work, I'd love to chat.
