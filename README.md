# DataAnalytics

# Crypto Market Sentiment vs Trader Behavior Analysis

This project analyzes how cryptocurrency trader behavior changes under different market sentiment conditions (Fear vs Greed) using historical trading data from Hyperliquid and the Bitcoin Fear & Greed Index.

The goal is to uncover patterns in profitability, trading volume, and risk-taking behavior that can help design smarter and more risk-aware trading strategies.

---

## Objective

- Study the relationship between market sentiment and trader behavior
- Compare profitability and trading activity during Fear vs Greed phases
- Identify risk patterns based on trade size
- Generate actionable insights for traders and trading platforms

---


---

## Tech Stack

- Python 3
- Pandas, NumPy
- Matplotlib, Seaborn
- Google Colab
- GitHub

---

## Datasets

1. Bitcoin Fear & Greed Index  
   Daily market sentiment classification (Fear / Greed)

2. Hyperliquid Historical Trades  
   Trade-level data including execution price, trade size, profit/loss, and timestamps

---

## How to Run (Google Colab)

1. Open `notebook_1.ipynb` in Google Colab  
2. Upload the datasets:
   - `hyperliquid_trades.csv`
   - `fear_greed.csv`
3. Run all cells in order  
4. Open `notebook_2.ipynb`  
5. Run all cells to generate:
   - CSV outputs in `csv_files/`
   - Charts in `outputs/`

Make sure folder creation cells are executed before saving files.

---

## Key Outputs

- Cleaned and merged dataset (`merged_data.csv`)
- Daily aggregated metrics (`daily_metrics.csv`)
- Visual analysis charts:
  - Average PnL by sentiment
  - Trading volume trends
  - Risk distribution by trade size
  - Feature correlation heatmap
- Final report: `ds_report.pdf`

---

## Summary of Findings

- Traders take larger positions during Greed phases
- Profit variability increases significantly during Greed
- Fear periods show reduced trading volume and smaller position sizes
- Trade size is weakly correlated with profitability
- Market sentiment is a useful indicator for risk management

Detailed results are documented in the final report.

---

## Author

Nimisha Agrawal  
Data Analyst / Data Science Candidate

---

## License

This project is for educational and evaluation purposes only.


