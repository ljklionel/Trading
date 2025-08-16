# Forex trading

---
Forex is the **largest financial market** in the world, with daily volume > $6 trillion.  
It operates **24 hours, 5 days a week**, unlike stock markets which have fixed sessions.  

💡 Why trade forex?  
- High liquidity (easy to enter/exit)  
- Leverage available  
- Accessible with low capital  

---

## What is Forex exactly? When can we trade?

- **Forex = Foreign Exchange.**  
  Example: EUR/USD = how many USD one Euro buys.  

- **Market Sessions:**
  - **Sydney:** 10pm – 7am GMT  
  - **Tokyo:** 12am – 9am GMT  
  - **London:** 8am – 5pm GMT  
  - **New York:** 1pm – 10pm GMT  

🔄 Liquidity is highest during **London–New York overlap**.

---

- **Forex = Foreign Exchange.**  
  Example: EUR/USD = how many USD one Euro buys.  

- **Market Sessions:**
  - **Sydney:** 10pm – 7am GMT  (6am - 3pm SGT)
  - **Tokyo:** 12am – 9am GMT  (8am - 5pm SGT)
  - **London:** 8am – 5pm GMT  (4pm - 1am SGT)
  - **New York:** 1pm – 10pm GMT  (9pm - 6am SGT)
 
- **Overlap periods in SGT**
  - Sydney + Tokyo: 8am - 3pm SGT
  - Tokyo + London: 4pm - 5pm SGT
  - London + New York (Highest liquidity): 9pm - 1am SGT 

🔄 Liquidity is highest during **London–New York overlap**.

- We are trading currency pairs which makes up of major currency pairs, minor currency pairs and exotic currency pairs. The pair we will want to trade in is major currency pair.
  - EUR/USD
    - EUR = Base currency, USD = Quote currency. This makes up the price of the pair 
    - EUR/USD = 1.08538. This means 1 EUR = 1.08538 USD
      - This means we will want to sell it at higher than 1.08538 to make money. Higher value = win
---

## What is Long/Short, Bullish/Bearish

- **Bullish (Buy/Long):** Expect price ↑  
- **Bearish (Sell/Short):** Expect price ↓  

```text
EUR/USD = 1.1000
Bullish: Expect → 1.1200 (Euro stronger)
Bearish: Expect → 1.0800 (Dollar stronger)
```

📊 Example chart:

```
Uptrend (Bullish)          Downtrend (Bearish)
   /                        \
  /                          \
 /                            \
```

---

## Trading Styles & Trend Identification

- **Scalping:** Seconds–minutes, small profits.  
- **Day Trading:** Intraday moves.  
- **Swing Trading:** Multi-day trends.  
- **Position Trading:** Weeks–months.  

📈 **Trend Anatomy:**
```
Uptrend:   Higher Highs (HH) & Higher Lows (HL)
Downtrend: Lower Highs (LH) & Lower Lows (LL)
```

ASCII Diagram:

```
Uptrend:   HL → HH → HL → HH
Downtrend: LH → LL → LH → LL
```

Proper Diagram:

![HHHLLHLL diagram](image/market_structure_hh_hl_lh_ll.png)

Recommended to start out swing trading. Easiest and most passive while mgetting massive profits.

### When to start / find the right market?

We will want to find a **trend** in the market (**UP OR DOWN**). This means we can get into a buy trade when the market is going up, or when the market starts to reverse, simply get 

Market go up: buy trade

Market go down: simply get out go short and profit

---

## PIPs, Technical vs Fundamental Analysis

- **PIP = Percentage in Point**
  - EUR/USD: 1 pip = 0.0001
  - USD/JPY: 1 pip = 0.01
  - We leave the smallest number off (the fraction).
  - 1.18538 -> 0.0003 = 1 pip; 0.005 = 10 pip; 0.08 = 100 pip; 0.1 = 1000 pip

- **Technical Analysis:**
  - Indicators: RSI, MACD, Moving Averages
  - Patterns: Double Top, Head & Shoulders

- **Fundamental Analysis:**
  - Interest rates
  - Inflation (CPI)
  - Employment (NFP)
  - Geopolitical events

---

##  Risk Management

⚠️ 90% of traders fail because of poor risk control.  

- Never risk > **2%** of account.  
- Use **stop loss** ALWAYS.  

📊 Risk Example:  
```
Account: $1,000
Risk per trade: 2% = $20
If Stop Loss = 20 pips → Lot size = $1/pip
```

---

## Choosing a Broker

Checklist:
- ✅ Regulation (FCA, ASIC, CySEC)  
- ✅ Spreads < 1 pip on majors  
- ✅ Good reputation (no slippage, withdrawal issues)  
- ✅ MT4/MT5 support  

---

##  Spread & Commission

- **Spread:** Difference between the buying price and the selling price that brokers offer
- **Commission:** Fixed $/lot charge.  

ASCII Example:  
```
EUR/USD
Bid: 1.1000 (Broker is willing to pay for an asset, which is always going to be slightly lower than the ask price)
Ask: 1.1002 (Dealer is willing to sell the currency pair at)
Spread: 2 pips
```

---

## Lot Sizes

| Lot Type   | Units    | Pip Value | Account balance |
|------------|----------|-----------| ----------------|
| Standard   | 100,000  | $10/pip   | $10000 or more  |
| Mini       | 10,000   | $1/pip    |                 |
| Micro      | 1,000    | $0.10/pip |                 | -> The one we will most likely be trading

---

## Leverage

- Leverage is money borrowed from the broker.
- Smallest possible trade we can open with a broker is 0.01 lots.
- **1:100 leverage** → control $100,000 with $1,000.  
- ⚠️ Misuse = margin calls.  

ASCII Illustration:
```
$1,000 Capital
1:100 Leverage
= $100,000 trade power
```

---

## Margin

- **Margin:** Required collateral.  
- **Free Margin:** Balance available for new trades.  
- **Margin Call:** Warning when equity < requirement.  

ASCII Illustration:
```
$10000 into account
Trading account with 1 to 30 leverage
$300000 worth of buying power
Open up to 3 lots
Margin = $10000
Broker will not let a loss exceed $10000
If broker sees loss close to $10000, they will do a margin call to ask for more deposit or start closing positions
```
---

## ⏱ 16:10 – 16:46 – Trading Account Setup

Steps:  
1. Choose broker  
2. Register & verify KYC  
3. Fund account  
4. Download MT5  (Metatrader 5)

---

## MetaTrader 5 Overview

Features:  
- Charting  
- Indicators  
- Automated trading (Expert Advisors)  
- Multiple timeframes  

---

## ⏱ Order Types
- **Current market price (CMP)**
  - This is the price right now on your chart
  - All pending orders are placed relative to CMP. Think of CMP as starting line.
- **Market Order:** Execute instantly.  
- **Pending Orders:**
  - Buy Stop 
  ```
  - Place above CMP
  - Triggered if price breaks resistance and continues upward
  - Usage: Expecting price to break resistance and continue higher

  EXAMPLE:
  - CMP = 1.1000
  - Resistance = 1.1050
  - Place Buy Stop = 1.1060
  - If resistance breaks → trade opens → profit if it keeps rising.

  Setup:
  - Entry: A few pips above resistance (to confirm breakout).
  - SL: Just below the resistance zone (in case of fakeout).
  - TP: Next resistance or target zone.

  EXAMPLE:
  - Resistance = 1.1050
  - Entry (Buy Stop) = 1.1060
  - SL = 1.1030
  - TP = 1.1120
  ```
  ![Buy stop](image/buy_stop_setup.png)
  
  - Sell Stop
  ```
  - Place below CMP
  - Triggered if price breaks support and keeps falling
  - Usage: Expecting price to break support and fall further

  EXAMPLE:
  - CMP = 1.1000
  - Support = 1.0950
  - Place Sell Stop = 1.0940
  - If support breaks → trade opens → profit if it continues down.

  Setup:
  - Entry: A few pips below support (to confirm breakdown).
  - SL: Just above the support zone.
  - TP: Next support zone below.

  EXAMPLE:
  - Resistance = 1.0950
  - Entry (Buy Stop) = 1.0940
  - SL = 1.0970
  - TP = 1.0880
  ```
  ![Sell stop](image/sell_stop_setup.png)
  
  - Buy Limit
  ```
  - Place below CMP
  - Triggered if price falls to support and bounces up
  - Usage: Expecting price to dip into support and bounce up.

  EXAMPLE:
  - CMP = 1.1000
  - Support = 1.0950
  - Place Buy Limit = 1.0950
  - If price dips to support and rebounds → you profit on the bounce.

  Setup:
  - Entry: At support level.
  - SL: A few pips below support.
  - TP: At or near the next resistance above.

  EXAMPLE:
  - Resistance = 1.0950
  - Entry (Buy Stop) = 1.0950
  - SL = 1.0920
  - TP = 1.1050
  ```
  ![Sell stop](image/buy_limit_setup.png)
  
  - Sell Limit  (Place above price and if market goes to that level, it will trigger a sell)
  ```
  - Place above CMP
  - Triggered if price rises to resistance and drops down
  - Usage: Expecting price to rally into resistance and bounce down.

  EXAMPLE:
  - CMP = 1.1000
  - Resistance = 1.1050
  - Place Sell Limit = 1.1050
  - If price rallies into resistance and reverses → you profit on the fall.

  Setup:
  - Entry: At resistance level.
  - SL: A few pips above resistance.
  - TP: At or near the next support below.

  EXAMPLE:
  - Resistance = 1.1050
  - Entry (Buy Stop) = 1.1050
  - SL = 1.1080
  - TP = 1.0950
  ```
  ![Sell stop](image/sell_limit_setup.png)
  
- Stops (Buy Stop / Sell Stop): Profit from breakouts (when price breaks through support/resistance).
- Limits (Buy Limit / Sell Limit): Profit from reversals (when price bounces off support/resistance).

---

## Stop Loss & Take Profit

- **Stop Loss (SL):** Safety net.  
- **Take Profit (TP):** Locks profit.  

Diagram:
```
Entry: 1.1000
TP:    1.1100  (+100 pips)
SL:    1.0950  (-50 pips)
```

---

## 📈 Risk:Reward (R:R) Strategy for Traders

Understanding Risk:Reward is crucial for long-term success in Forex.

🔹 What is Risk:Reward Ratio?
- **Risk:** How much you’re willing to lose (Stop Loss).  
- **Reward:** How much you aim to gain (Take Profit).  
- **Formula:** R:R = Reward ÷ Risk.

👉 Example:  
- Risk = $1,000  
- Reward = $5,000  
- **R:R = 5:1** ✅

---

📊 Risk:Reward Ratios Diagram
![Risk Reward Ratios](risk_reward_ratios.png)

---

📊 R:R Ratio Table

| Ratio | Meaning | Example (100 pip SL) | Comment |
|-------|---------|----------------------|---------|
| **1:1** | Risk $1 to make $1 | SL = 100 pips, TP = 100 pips | Break-even long term, needs high win rate |
| **1:2** | Risk $1 to make $2 | SL = 100 pips, TP = 200 pips | Standard target for most traders |
| **1:3** | Risk $1 to make $3 | SL = 100 pips, TP = 300 pips | Very profitable, can succeed with 40% win rate |
| **1:5** | Risk $1 to make $5 | SL = 100 pips, TP = 500 pips | Excellent setups, even 25% win rate is profitable |

---

✅ Key Insights
- Always **set Stop Loss (risk) first**.  
- Aim for **1:2 or better** for consistent profitability.  
- Higher R:R = fewer winning trades needed.  
- Example ($1k SL, $5k TP) = **1:5**, excellent setup.

---

## Capital & Prop Firms

- Minimum recommended: $500–$1,000.  
- **Prop firms** fund traders after evaluation:  
  - Example: FTMO, MyForexFunds.  
  - Pass → manage $100k, profit split 80/20.  

---

## Trading Psychology

- Emotions = trader’s worst enemy.  
- Avoid: revenge trading, overleveraging.  
- Key traits: discipline, patience, consistency.  

---

## Chart Analysis

- **Candlesticks:**
  ```
  |‾‾‾|   ← Bullish body (close > open)
  |   |
  |___|
  ```
- **Trends:** Uptrend, downtrend, sideways.  
- **Supply/Demand zones:** Institutional buying/selling areas.
  - To look for demand zone, find the sideway trend just before the uptrend. That is where we aim to set our buy limit and we set our stop loss below this demand
  - To look for supply zone, find the sideway trend just after the down trend. That is where we expect the market to push from the demand to the supply.
- **Entry strategy:** Confirm on higher timeframe → execute on lower timeframe.
  - Concept: Confirm entries on smaller charts (e.g., 15m or 5m).
  - Higher TF (4H/Daily) shows bullish trend.
  - Drop to 15m → look for bullish candlestick pattern inside demand zone.

### Strategies

1. Trend Following (HH/HL & LH/LL)
   
    **Concept:** Trade in the direction of the trend (uptrend = buy, downtrend = sell).  
    **How to Spot:** Look for **Higher Highs & Higher Lows (HH/HL)** in uptrend, or **Lower Highs & Lower Lows (LH/LL)** in downtrend.  
    
    **EUR/USD Example:**  
    - 1.0800 → 1.1000 → 1.0900 → 1.1200 = **Uptrend**  
    - ✅ Strategy: Buy on pullbacks (at Higher Lows).  

2. Support & Resistance Trading
   
    **Concept:** Price often reacts at key levels where it reversed before.  
    **How to Spot:** Draw horizontal lines at previous swing highs/lows.  
    
    **EUR/USD Example:**  
    - Support = **1.0900**  
    - Resistance = **1.1100**  
    - If price is near 1.0900 → look for **buy** opportunities.  
    - If price is near 1.1100 → look for **sell** opportunities.

3. Breakout Trading

    **Concept:** Trade when price breaks out of a consolidation zone (range).  

    **EUR/USD Example:**  
    - Range = 1.0950 – 1.1050  
    - Place **Buy Stop** above 1.1060 (breakout up).  
    - Place **Sell Stop** below 1.0940 (breakout down).  
    - Profit if momentum continues.

4. Pullback / Retracement Trading

    **Concept:** After a strong move, price often retraces before continuing trend.  
    **Tool:** Fibonacci retracement (38.2%, 50%, 61.8%).  
    
    **EUR/USD Example:**  
    - Price rallies from 1.0800 → 1.1200.  
    - Expect pullback to **1.1000** (50% retracement).  
    - ✅ Enter Buy at 1.1000 for continuation upwards.

5. Moving Average (MA) Strategy

    **Concept:** Use moving averages to identify trend & entries.  

    **EUR/USD Example:**  
    - Apply **50-day and 200-day MA**.  
    - 50 MA crosses above 200 MA → **Golden Cross** (buy signal).  
    - 50 MA crosses below 200 MA → **Death Cross** (sell signal).

6. Candlestick Pattern Trading

    **Concept:** Candlesticks reveal reversal or continuation signals.  

    **Common Patterns:**  
    - Bullish Engulfing (buy signal)  
    - Bearish Engulfing (sell signal)  
    - Doji (indecision)  
    
    **EUR/USD Example:**  
    - At **1.0950 support**, a **Bullish Engulfing candle** appears → Buy setup.

7. Risk-Reward & Trade Management

    **Concept:** Never trade without SL and TP.  

    **EUR/USD Example:**  
    - Entry = 1.1000  
    - SL = 1.0950 (risk 50 pips)  
    - TP = 1.1100 (reward 100 pips)  
    - ✅ R:R = 1:2 (good trade).
  
![strategies](image/eurusd_strategy_integration_sl_tp.png)
---

## Trade Setup Example

- Identifies demand zone.  
- Places long trade with SL under zone.  
- Example outcome: +$18,000.  

---

# ⚠️ Cautionary Notes

- Forex = **high risk**.  
- Marketing promises are **unrealistic** for beginners.  
- Only invest money you can afford to lose.  

---

# ✅ Final Takeaways

- Learn **risk management first**.  
- Use **demo accounts** before trading live.  
- Focus on **discipline and consistency**, not “get rich quick”.  
- Forex is a **marathon, not a sprint**.  

---
