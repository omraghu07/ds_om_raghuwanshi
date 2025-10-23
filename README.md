# ds_om_raghuwanshi


## 🎯 Project Overview

**Trader Behavior vs Market Sentiment Analysis** is a comprehensive **data science project** that explores the relationship between **trader behavior on the Hyperliquid exchange** and the **Bitcoin market sentiment index (Fear vs. Greed)**.

The goal is to uncover **hidden patterns** in trading behavior — such as profitability, leverage usage, risk exposure, and trade volume — and how they correlate with market psychology.  
This helps identify actionable insights for **smarter Web3 trading strategies** and risk-aware decision-making.



## 🧠 Key Objectives

- Analyze how trader activity aligns or diverges from overall market sentiment.  
- Identify behavioral differences during **Fear** vs. **Greed** phases.  
- Explore whether sentiment can predict trading profitability and risk appetite.  
- Develop a **machine learning model** to predict market sentiment from trader data.  
- Generate a **data-driven strategy framework** for traders and analysts.

---

## 🧩 Analytical Pipeline

### 1. **Data Preprocessing & Integration**
- **Temporal alignment** between sentiment and trading datasets.  
- Handling **missing values**, duplicates, and inconsistent column names.  
- **Feature engineering**: derived metrics such as:
  - Profit ratios
  - Risk exposure
  - Position size normalization
  - Leverage-to-volume ratio

### 2. **Exploratory Data Analysis (EDA)**
- Distribution plots of PnL, leverage, and trade size.  
- Behavioral shifts during Fear vs. Greed periods.  
- Correlation heatmaps between trading metrics and sentiment scores.

### 3. **Statistical Testing**
- **Welch’s T-Test** – Mean differences in profitability between Fear/Greed periods.  
- **Mann–Whitney U Test** – Non-parametric significance testing.  
- **Chi-Square Test** – Association between sentiment class and win rates.  
- Confidence level: **α = 0.05**.

### 4. **Machine Learning Modeling**
- **Random Forest Classifier** trained to predict sentiment based on trader metrics.  
- Feature importance ranking for interpretability.  
- Model evaluation: accuracy, precision, recall, and F1-score.

### 5. **Visualization & Insights**
- Interactive **Plotly dashboards** for dynamic exploration.  
- Comparative trend plots showing behavior shifts across market sentiment phases.  
- Exportable reports (`summary_statistics.csv`, `executive_insights_report.txt`).

---
