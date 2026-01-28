# Trader Behavior Analysis vs Market Sentiment

## Objective
The goal of this project is to analyze the relationship between market sentiment (Fear, Neutral, Greed) and trader performance (Closed PnL, Win Rate, Buy/Sell behavior) using historical trading data.

---

## Datasets
1. **historical_data.csv** – Historical trades of traders  
2. **fear_greed_index.csv** – Daily market sentiment (Fear, Neutral, Greed)

---

## Key Insights

1. **Extreme Greed yields highest profitability**
   - Average Closed PnL is highest during Extreme Greed days.
   - Win rate is also highest in Extreme Greed.
   
2. **Fear periods show lower performance**
   - Average PnL and win rates drop during Fear / Extreme Fear phases.
   - Suggests cautious or reactive trading behavior.

3. **Buy vs Sell behavior**
   - Buy trades dominate during Greed phases.
   - Fear periods see more selling activity.

4. **Time-series trends**
   - Daily trend charts show clear patterns: peaks in Extreme Greed, dips in Fear.
   - Helps understand behavioral patterns over time.

---

## Recommendation
- Traders should monitor market sentiment to adjust strategy and manage risk.  
- Visual analysis provides actionable insights for better decision-making.

---

## Libraries Used
- Python (Pandas, NumPy, Matplotlib, Seaborn)  
- Jupyter Notebook

---

## How to Run
1. Open `Trader_Behavior_Analysis.ipynb` in Jupyter Notebook  
2. Run all cells in order to reproduce analysis and charts  
3. Make sure the datasets `historical_data.csv` and `fear_greed_index.csv` are in the same folder

---

## Author
**Antra Chauhan**  
**Date:** 28 Jan 2026
