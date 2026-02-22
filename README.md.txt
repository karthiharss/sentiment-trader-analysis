Project Explanation

Project Overview

This project analyzes how cryptocurrency trader behavior and profitability change under different market sentiment conditions — specifically Fear and Greed periods.

The analysis combines:

Historical trading data
Fear & Greed Index data

The objective is to evaluate whether market sentiment influences profitability, risk-taking behavior, and trading frequency.

Problem Statement

Market sentiment plays a major role in financial markets.
However, most traders do not systematically adjust their strategy based on sentiment shifts.

Project Structure

Round0/
│
├── analysis.py            
├── fear_greed_index.csv   
├── historical_data.csv    
├── README.md              
└── charts/

Requirements

Make sure you have:

Python 3.9 or above
pip installed

Required Python Libraries
matplotlib
scikit-learn

How to Run the Project
Step 1: Open Terminal / Command Prompt

Navigate to your project folder:

cd path_to_your_folder/Round0

Step 2: Run the Script

If using a Python file:

python analysis.py

Methodology

Data Loading

Imported historical trading data
Imported Fear & Greed Index dataset

2. Data Preprocessing

Converted timestamps to date format
Merged trading data with daily sentiment values
Created a daily-level dataset

3. Feature Engineering
Calculated:

Daily PnL
Win rate
Number of trades per day
Average trade size
Volatility of PnL

4. Exploratory Analysis

Compared Fear vs Greed periods
Analyzed behavioral differences
Created visualizations

Key Insights

Higher Risk-Taking During Greed
Traders increase trade size and frequency during Greed periods.

2. Higher Volatility During Fear
Fear periods show greater PnL fluctuation and inconsistent performance.

3. Profitability Differences
Average daily PnL tends to be higher during Greed conditions, but risk exposure is also elevated.

4. Behavioral Segments Exist
Clustering reveals distinct trader types:

Conservative consistent performers
High-risk aggressive traders
Inconsistent speculative traders

5. Sentiment Influences Behavior
Market sentiment clearly affects trading patterns and risk appetite.

Strategy Recommendations
Rule 1: Risk Adjustment During Fear
During Fear periods, traders should reduce leverage and position size to manage volatility and protect capital.

Rule 2: Selective Aggression During Greed
During Greed periods, increase trade frequency or exposure only for traders with historically high win rates and stable performance.
