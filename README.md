# Real-Time Detection and Risk Management of Bitcoin Bubbles Using LPPLS and Sentiment

We propose a real-time framework for tracking the evolution of speculative bubbles in the Bitcoin market, leveraging both structural (endogenous) and sentiment (exogenous) signals to incorporate bubble risk management into an Automated Trading System. In particular, we develop an indicator using features derived from the Log-Periodic Power Law Singularity (LPPLS) model to detect bubble formation and explosion, and evaluate its effectiveness by backtesting a strategy that uses this score within prefixed time horizons. We then compare it with strategies that employ different combinations of our indicator with the Fear and Greed Index (FGI), a sentiment proxy frequently used in cryptocurrency analysis, as well as with standard risk analysis techniques such as volatility targeting and trend following. The results show that although passive exposure remains difficult to outperform during strong bullish cycles, the proposed strategies reduce maximum drawdowns by up to 50% compared to passive exposure in adverse market conditions. 

This repository contains materials from our study. It includes:
- A dataset.
- A Python notebook for detailed analysis of the data.

## Contents

- `dfA.csv`: comprising Bitcoin prices, from 2018 to March 2026.
- `Bitcoin_Bubble_Risk_Management.ipynb`: Python notebook for data analysis.

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Risk-Management-of-Bitcoin-Bubbles.git
2. Ensure all files are in the same directory.
3. Open the Python notebook using Jupyter Notebook or JupyterLab to explore the analysis.
4. The notebook uses a dataset as input with Bitcoin price and the Fear and Greed Index.
