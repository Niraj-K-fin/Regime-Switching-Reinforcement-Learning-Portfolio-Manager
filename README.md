# Regime-Switching-Reinforcement-Learning-Portfolio-Manager
🚀 Adaptive Trading Agent for Real-World Markets

## Overview ##
In traditional finance, most portfolio models assume stationarity — that markets behave consistently over time.
But reality is different: markets shift between bull runs, bear crashes, and volatile sideways patterns.

This project builds a Reinforcement Learning (RL) agent that doesn't just trade —
it detects market regimes dynamically and adapts its trading strategy in real-time.

✅ Market Regime Detection (Bull, Bear, Sideways)
✅ Reinforcement Learning (Q-Learning / PPO)
✅ Fully CPU-compatible (no GPU required)
✅ Built using Python, NumPy, Stable-Baselines3, and lightweight libraries

## Key Features ##
### Regime Awareness:
Uses Gaussian Mixture Models (GMM) to classify historical market behavior into different regimes.

### Dynamic Strategy Adaptation
The agent modifies its buy/hold/sell decisions based on the current market regime.

### Reward-Based Learning:
The agent learns from profits and penalties over time to improve its portfolio management decisions.

### Risk-Return Optimization:
Fine-tuned to balance maximizing returns while controlling for regime-based risk.

## Tech Stack
🐍 Python 3

📦 Libraries:

Stable-Baselines3

Gymnasium

Numpy

Pandas

Scikit-learn

yFinance

Technical Analysis (ta-lib)

🎯 Reinforcement Learning: PPO (Proximal Policy Optimization)

📈 Regime Detection: Gaussian Mixture Models (GMM)

### Workflow
#### Install dependencies:

bash
Copy
Edit
pip install stable-baselines3 gymnasium shimmy yfinance ta pandas numpy scikit-learn matplotlib seaborn
Download historical price data:

Asset: SPY (S&P 500 ETF)

Source: Yahoo Finance

Preprocess data:

Calculate daily returns and 10-day volatility.

Fit a GMM model to label regimes.

Create a custom trading environment:

Observations: [Current price, Previous price, Balance, Shares held]

Actions: Buy, Hold, Sell

Train RL Agent:

Using PPO for robust learning across multiple market conditions.

Test & Evaluate:

Simulate real-world trading.

Compare performance vs static strategies.

### Demo
🎬 Video Demo Available:
(attached if posting on LinkedIn / GitHub Releases)

Watch the full walkthrough showing model training, live trading simulation, and regime adaptability.

### Results
Successfully detects and adapts to changing market regimes.

Demonstrates better risk-adjusted performance compared to static trading policies.

All training done on CPU without heavy hardware requirements.

### Future Improvements
Integrate more sophisticated regime indicators (e.g., macroeconomic signals).

Expand asset universe to multi-asset portfolios.

Deploy in a simulated live environment with real-time data feed.

### Acknowledgments
Thanks to open-source communities in RL, quantitative finance, and data science —
without whom this project would not be possible.
