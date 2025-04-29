# Regime-Switching Reinforcement Learning Portfolio Manager

> **An intelligent, adaptive investment system that learns to read the market, respond to change, and optimize returns.**

---

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)
![Stable-Baselines3](https://img.shields.io/badge/Stable--Baselines3-rl-yellow?logo=python)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 🚀 Overview

This project implements a next-generation, AI-powered portfolio manager that combines **reinforcement learning (RL)** with **market regime detection** and **macroeconomic signals**. The result is an agent that dynamically allocates assets, manages risk, and adapts to ever-changing financial markets-just like a real-world quant.

---

## 🛠️ Tech Stack

- **Programming Language:** Python 3.8+
- **Machine Learning:** [Stable-Baselines3](https://github.com/DLR-RM/stable-baselines3) (PPO)
- **RL Environment:** Custom [OpenAI Gym](https://www.gymlibrary.dev/) environment
- **Data Handling:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn
- **Technical Indicators:** TA-Lib, custom code
- **Jupyter/Colab:** For interactive exploration and prototyping

---

## ✨ Key Features

- **Market Regime Detection:**  
  Uses technical indicators (Bollinger Bands, RSI, MACD) to identify bull, bear, and neutral market states for each asset.
- **Macro-Aware Decision Making:**  
  Integrates VIX and 10-year Treasury yields for a holistic market perspective.
- **Volatility Targeting:**  
  Dynamically scales positions based on recent volatility to manage risk.
- **Robust Risk Controls:**  
  Models transaction costs, trailing stop-loss, and take-profit mechanisms for realistic trading.
- **Continuous, Fine-Grained Allocation:**  
  Allocates fractional weights across multiple assets for optimal flexibility.
- **Custom OpenAI Gym Environment:**  
  Simulates multi-asset trading with historical ETF data (SPY, QQQ, TLT, GLD).
- **State-of-the-Art RL Training:**  
  Powered by Proximal Policy Optimization (PPO).

---

## 📈 Model Training Results

- **Adaptive portfolio allocation** that responds to market regimes and macro trends.
- **Improved Sharpe ratios** and **controlled drawdowns** in backtests.
- **Stable training** with increasing episode rewards and value function accuracy.

---

## 📚 How It Works

- **Environment:**  
  Custom Gym environment simulates trading with regime detection, macro features, and realistic constraints.
- **Agent:**  
  PPO agent learns to allocate capital adaptively, balancing risk and reward.
- **Data:**  
  Four years of historical ETF data (SPY, QQQ, TLT, GLD) + macro indicators.
- **Performance:**  
  Evaluated via backtesting, with metrics like Sharpe ratio and max drawdown.

---

## 🧠 Why It Matters

Traditional portfolio strategies are often static or rule-based. This project shows how AI can learn to **adapt on the fly**, managing risk and seizing opportunities as market conditions evolve.

---

## 🙌 Contributing

Contributions, suggestions, and forks are welcome! Please open an issue or pull request.

---

## 📄 License

MIT License

---

## 💡 Inspiration

Inspired by the intersection of quantitative finance and artificial intelligence, this project aims to bridge the gap between academic RL models and real-world portfolio management.

---

**Ready to see AI in action on Wall Street? Dive in, experiment, and let’s build the future of investing together!**
