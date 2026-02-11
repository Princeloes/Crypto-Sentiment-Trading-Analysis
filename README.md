# 📊 Trader Performance vs. Market Sentiment

### 🚀 Project Overview
This project analyzes over 7,000+ real crypto trades to determine if "Market Sentiment" (Fear & Greed Index) acts as a leading indicator for trader profitability. By merging historical trade logs with daily sentiment data, we uncover behavioral patterns in risk management, leverage, and win rates.

### 📂 Dataset
- **Trader Data:** Historical trade logs from Hyperliquid (Entry/Exit, PnL, Size, Side).
- **Market Sentiment:** Daily "Fear and Greed Index" values (0-100).

---

### 🔍 Key Insights
1.  **Greed is Good (For Momentum):**
    - Contrary to the "contrarian" belief, traders in this dataset performed **best** during **"Extreme Greed"** periods.
    - **Avg PnL:** Highest in Greed zones.
    - **Win Rate:** Peaked at ~46% during high sentiment.

2.  **The "Dip Buying" Phenomenon:**
    - During **"Extreme Fear"**, the Long/Short ratio flipped to **51% Buy**, indicating traders systematically bid on panic dumps.
    - During **"Extreme Greed"**, selling pressure increased (55% Sell), suggesting profit-taking.

3.  **Risk Behavior:**
    - Average **Trade Size ($)** increased significantly during Greed days, showing that confidence (and potentially leverage) correlates with market sentiment.

---

### 💡 Strategy Recommendations
Based on the data, here are two actionable rules for a trading system:

1.  **The "Momentum" Rule:**
    - *Condition:* When Fear & Greed Index > 75 (Extreme Greed).
    - *Action:* Increase position sizing by 20%. The data shows this is the "sweet spot" for retail profitability, likely due to strong trending markets.

2.  **The "Chop" Filter:**
    - *Condition:* When Sentiment is "Neutral" (45-55).
    - *Action:* Reduce trade frequency. This zone showed the lowest average PnL, suggesting lack of clear direction leads to over-trading losses.

---

### 🛠️ How to Run
1. Clone the repo:
   ```bash
   git clone [https://github.com/Princeloes/Crypto-Sentiment-Trading-Analysis.git](https://github.com/Princeloes/Crypto-Sentiment-Trading-Analysis.git)# Crypto-Sentiment-Trading-Analysis
Analyzing how market sentiment (Fear &amp; Greed) impacts trader profitability and risk behavior.
