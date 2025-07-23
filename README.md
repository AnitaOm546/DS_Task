# 📊 Trader Performance vs Bitcoin Market Sentiment

## 🎯 Objective
Explore the relationship between trader performance and Bitcoin market sentiment, uncover hidden behavioral patterns, and generate insights to optimize trading strategies.

---

## 📆 Assignment Overview
This project leverages two key datasets to analyze how market sentiment (Fear/Greed) influences trader behavior and outcomes.

### 📊 Datasets Used:

#### 1. **Bitcoin Market Sentiment Dataset**
- **Columns**: `Date`, `Classification` *(Fear / Greed)*  
- Represents daily sentiment ratings for the crypto market.

#### 2. **Historical Trader Data from Hyperliquid**
- **Columns include**:
  - `account`, `symbol`, `execution price`, `size`, `side`, `time`,  
  - `start position`, `event`, `closedPnL`, `leverage`, etc.
- Contains transaction-level trading data for individual traders.

---

## 🔀 Workflow

1. **Data Integration**
   - Merge market sentiment data with trader performance based on timestamps/dates.

2. **Data Cleaning & Preparation**
   - Handle missing values and format columns
   - Normalize metrics like PnL and leverage

3. **Exploratory Data Analysis (EDA)**
   - Identify performance trends under Fear vs. Greed conditions
   - Explore leverage usage, PnL distribution, and trade volumes

4. **Feature Engineering**
   - Create sentiment-based trading features (e.g., avg. PnL under Greed)
   - Categorize trader strategies or profiles

5. **Pattern Discovery & Visualization**
   - Visualize trading outcomes by sentiment class
   - Cluster trader behavior patterns

6. **Insight Generation**
   - Summarize actionable insights for improving trade strategies based on sentiment shifts

---

## 🔧 Tools & Technologies
- **Python**, **Pandas**, **NumPy**  
- **Matplotlib**, **Seaborn**  
- **Scikit-learn** for modeling & clustering

---

## ✅ Outcome
Discovered significant patterns in trader behavior tied to market sentiment. Traders using high leverage performed poorly during 'Fear' days. These insights can inform both risk management and predictive modeling for future trading strategies.
