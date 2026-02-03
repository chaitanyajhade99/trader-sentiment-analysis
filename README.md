# Trader Performance vs Market Sentiment

## Objective
Analyze how Bitcoin market sentiment (Fear and Greed) affects trader
behavior and performance on the Hyperliquid trading platform, and
derive actionable trading insights.

---

## Datasets
- **Bitcoin Market Sentiment Dataset**: Daily Fear/Greed classification.
- **Hyperliquid Historical Trader Data**: Trade-level data including
  account, timestamp, trade size, direction, and closed PnL.

---

## Setup
Ensure Python **3.9+** is installed, then install dependencies:
pip install pandas numpy matplotlib seaborn scikit-learn


---

## How to Run
1. Place dataset files in the `Data/` folder.
2. Open `notebook.ipynb`.
3. Run all cells from top to bottom.

---

## Key Insights
- Traders take larger positions and trade more frequently during Greed days.
- Losses are sharper during Fear periods.
- Frequent traders adapt better to Fear regimes.

---

## Strategy Recommendations
- Reduce position sizes during Fear days.
- Increase activity during Fear only for frequent traders.

---

## Notes
- Leverage data was not available; trade size (USD) was used as a proxy
  for risk exposure.


