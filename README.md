
# 📊Trader Performance Analysis Across Market Sentiment Regimes

This project analyzes how trader performance, risk, and behavior vary across different market sentiment regimes using historical trade execution data aligned with the Fear & Greed Index.

Rather than treating sentiment as a predictive intraday signal, this analysis uses sentiment as a contextual market regime, allowing for a realistic assessment of how traders perform under Fear, Greed, and extreme market conditions.


## 🎯Objective

1.Analyze trade distribution across market sentiment regimes

2.Compare trader profitability and consistency under different sentiments

3.Examine the relationship between risk and return

4.Identify top-performing traders per sentiment regime

5.Detect contrarian traders who outperform during Fear-driven markets
## 🗂️Dataset Description

1️⃣ Fear & Greed Index

Daily market sentiment classification

Categories: Extreme Fear, Fear, Neutral, Greed, Extreme Greed

2️⃣ Trade Execution Data

Individual trade records with PnL, trade size, fees, and timestamps

Aggregated at Trader × Sentiment Regime level for analysis
## 🔍Key Analysis Questions & Insights

**Key Analysis Questions**

Q1.How is market sentiment distributed across the dataset?

Q2.Do traders behave differently under different sentiment regimes?

Q3.Is higher return accompanied by higher risk?

Q4.Who performs best under each sentiment regime?

Q5.Are there traders who outperform during Fear markets?

**Key Insights**

1.Market sentiment coverage is well distributed, enabling robust comparative analysis

2.Greed regimes show higher profitability accompanied by increased risk

3.Fear regimes exhibit more conservative risk-return profiles

4.Top traders vary significantly across sentiment regimes

5.A subset of traders demonstrates contrarian behavior, outperforming during Fear markets


## ▶️Run Locally

**How to Run**

Open notebook_1.ipynb in Google Colab

Ensure all CSV files are placed inside the csv_files/ directory

Run all cells sequentially

Generated outputs and visualizations will be saved in the outputs/ folder
## 🧰Tech Stack

**Python**

**Pandas, NumPy**

**Matplotlib, Seaborn**

**Google Colab**

