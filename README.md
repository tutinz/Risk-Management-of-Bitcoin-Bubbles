# Real-Time Detection and Risk Management of Bitcoin Bubbles Using LPPLS and Sentiment

This paper proposes a real-time framework for tracking the evolution of speculative bubbles in the Bitcoin market using structural (endogenous) and sentiment (exogenous) signals, with the goal of testing strategies and eventually incorporating risk management during bubbles in an Automated Trading System. In particular, we develop a bubble score from Bitcoin's daily closing prices, using features derived from the LPPLS model to detect bubble formation and explosion, and attempt to validate its efficiency by backtesting a strategy that uses that score within prefixed time horizons. We compare the outcome with strategies that employ different combinations of the LPPLS Bubble Score and the Fear and Greed Index. Results show that, although passive exposure remains difficult to outperform during strong bullish cycles, the proposed LPPLS and sentiment-based strategies significantly reduce drawdowns and improve portfolio stability, particularly during volatile and adverse market conditions.

This repository contains materials from our study. It includes:
- A dataset.
- A Python notebook for detailed analysis of the data.

## Contents

- `df.csv`: comprising Bitcoin prices, from January 2012 to September 2025.
- `DataAnalisys.iynb`: Python notebook for data analysis.

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Risk-Management-of-Bitcoin-Bubbles.git
2. Ensure all files are in the same directory.
3. Open the Python notebook using Jupyter Notebook or JupyterLab to explore the analysis.
4. The notebook uses a dataset as input with Bitcoin price and the Fear and Greed Index.
