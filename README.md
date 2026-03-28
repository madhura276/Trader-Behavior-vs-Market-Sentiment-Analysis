# 📊 Trader Behavior vs Market Sentiment Analysis

## 📌 Project Overview
This project analyzes the relationship between Bitcoin market sentiment (Fear & Greed Index) and trader performance using historical trading data.

The goal is to understand how market emotions influence profitability, trading activity, and risk behavior.

---

## 📂 Datasets Used

### 1. Bitcoin Market Sentiment Dataset
- Columns: Date, Classification (Fear, Greed, Extreme Fear, Extreme Greed, Neutral)

### 2. Historical Trader Data (Hyperliquid)
- Columns include: Account, Coin, Execution Price, Size, Side, Timestamp, Closed PnL, etc.

---

## ⚙️ Approach

1. **Data Cleaning**
   - Standardized column names
   - Converted timestamps to date format
   - Handled missing and inconsistent values

2. **Data Alignment**
   - The datasets had different year ranges (2018 vs 2024)
   - Merged data using **day-month mapping** to align sentiment with trades

3. **Feature Engineering**
   - Created profit flag (`is_profit`)
   - Extracted relevant trading metrics

4. **Analysis Performed**
   - Average Profit (PnL) by sentiment
   - Win rate across sentiment categories
   - Trading activity distribution
   - Behavioral pattern analysis

---

## 📊 Key Insights

- Traders achieve **higher profitability during Greed phases**, supported by bullish market conditions.
- **Extreme Fear leads to higher losses**, indicating panic-driven trading decisions.
- The **win rate is higher in Greed**, showing better success in positive market sentiment.
- Trading activity increases during **Fear and Greed**, highlighting emotional trading behavior.

---

## 📌 Conclusion

The analysis shows that market sentiment significantly impacts trader performance.

- Positive sentiment improves profitability and success rate
- Negative sentiment leads to higher losses and unstable outcomes
- Emotional market conditions drive trading activity

Incorporating sentiment analysis can help traders make more informed and strategic decisions.

---

## 🚀 Business Impact

- Helps traders adjust strategies based on market sentiment
- Supports better risk management during volatile conditions
- Enables development of data-driven trading models

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📁 Project Structure
trader-sentiment-analysis/
│
├── data/
├── notebooks/
│ └── analysis.ipynb
├── README.md