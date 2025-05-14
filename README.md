# 📈 Crypto_Assignment

## 🚀 Objective
This project aims to analyze the relationship between **Bitcoin market sentiment** (Fear & Greed Index) and **trader performance** using historical trading data. The ultimate goal is to uncover hidden patterns that can lead to **smarter trading strategies**.

---

## 📂 Datasets

### 1. Historical Trader Data from Hyperliquid
- **File:** `historical_data.csv`
- **Download Link:** [Click here](https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view)

### 2. Bitcoin Market Sentiment (Fear & Greed Index)
- **File:** `fear_greed_index.csv`
- **Download Link:** [Click here](https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf/view)

---

## 🛠️ Steps Performed

1. **Data Cleaning & Preprocessing**
   - Converted `Timestamp IST` to datetime and extracted date.
   - Aligned sentiment `date` with trading data `date`.
   - Merged both datasets on the `date` column.

2. **Exploratory Data Analysis (EDA)**
   - Count of trades under each sentiment classification.
   - Mean and median `Closed PnL` per sentiment.
   - Win rate calculation (`Closed PnL > 0`) per sentiment.
   - Leverage and risk behavior (if applicable).
   - Visualizations using Seaborn and Matplotlib.

3. **Insight Discovery**
   - Traders tend to be more active during Greed/Extreme Greed.
   - PnL is more volatile during Greed periods.
   - Conservative behavior observed during Fear.
   - Contrarian strategies (trading opposite sentiment) can be profitable.

---

## 📊 Key Insights

| Insight | Implication |
|--------|-------------|
| Greed days have higher trade volume | Traders are more active and take on more risk |
| Fear days show lower volatility | Opportunity for conservative, risk-managed entries |
| High leverage during Greed | Risk of amplified losses — dynamic risk control advised |
| Contrarian trades perform well | Potential to build sentiment-aware algo strategies |

---

## 🧠 Strategy Recommendations

- Use **sentiment as a feature** in risk models.
- Apply **position sizing** and **leverage control** based on sentiment.
- Explore **contrarian entries** during Fear for long-term holds.

---

## 📎 Files in Repo

- `historical_data.csv` — Trader performance data
- `fear_greed_index.csv` — Market sentiment data
- `merged_trader_sentiment_data.csv` — Final cleaned dataset
- `crypto_analysis.ipynb` — Jupyter Notebook with full analysis
- `README.md` — Project overview (this file)

---
