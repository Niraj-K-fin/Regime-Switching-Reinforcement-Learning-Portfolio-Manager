<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
</head>
<body>

<h1>📈 Regime-Switching Reinforcement Learning Portfolio Manager</h1>

<p><strong>Adaptive Trading Agent for Real-World Markets</strong></p>

<hr>

<h2>🌟 Overview</h2>

<p>In traditional finance, portfolio models often assume <em>stationarity</em> — that markets behave consistently over time.<br>
But real-world markets don't: they shift between <strong>bull runs</strong>, <strong>bear crashes</strong>, and <strong>volatile sideways patterns</strong>.</p>

<p>This project builds a <strong>Reinforcement Learning (RL)</strong> agent that <strong>detects</strong> market regimes dynamically and <strong>adapts</strong> its trading strategy in real-time.</p>

<ul>
  <li>✅ Market Regime Detection (Bull, Bear, Sideways)</li>
  <li>✅ Reinforcement Learning (Q-Learning / PPO)</li>
  <li>✅ Fully CPU-compatible (no GPU required)</li>
  <li>✅ Built with Python, NumPy, Stable-Baselines3, and lightweight libraries</li>
</ul>

<hr>

<h2>🚀 Key Features</h2>

<ul>
  <li><strong>Regime Awareness:</strong> Uses Gaussian Mixture Models (GMM) to classify historical market behavior into different regimes.</li>
  <li><strong>Dynamic Strategy Adaptation:</strong> The agent modifies its buy/hold/sell decisions based on the current detected regime.</li>
  <li><strong>Reward-Based Learning:</strong> Learns from profits (rewards) and penalties (losses) to improve trading decisions over time.</li>
  <li><strong>Risk-Return Optimization:</strong> Balances maximizing returns while controlling for regime-specific risks.</li>
</ul>

<hr>

<h2>🛠️ Tech Stack</h2>

<ul>
  <li>🐍 Python 3</li>
  <li>📦 Libraries:
    <ul>
      <li>Stable-Baselines3</li>
      <li>Gymnasium</li>
      <li>Numpy</li>
      <li>Pandas</li>
      <li>Scikit-learn</li>
      <li>yFinance</li>
      <li>Technical Analysis Library (ta-lib)</li>
    </ul>
  </li>
  <li>🎯 RL Algorithm: PPO (Proximal Policy Optimization)</li>
  <li>📈 Regime Detection: Gaussian Mixture Models (GMM)</li>
</ul>

<hr>

<h2>🔧 Workflow</h2>

<ol>
  <li><strong>Install dependencies:</strong><br>
    <code>pip install stable-baselines3 gymnasium shimmy yfinance ta pandas numpy scikit-learn matplotlib seaborn</code>
  </li>
  <li><strong>Download historical price data:</strong><br>
    - Asset: SPY (S&P 500 ETF)<br>
    - Source: Yahoo Finance
  </li>
  <li><strong>Preprocess data:</strong><br>
    - Calculate daily returns and rolling volatility.<br>
    - Apply GMM for regime labeling.
  </li>
  <li><strong>Create a custom trading environment:</strong><br>
    - Observations: [Current price, Previous price, Balance, Shares held]<br>
    - Actions: Buy, Hold, Sell
  </li>
  <li><strong>Train the RL agent:</strong><br>
    - Using PPO algorithm to learn across multiple regimes.
  </li>
  <li><strong>Test & Evaluate:</strong><br>
    - Simulate real-world trading.<br>
    - Compare adaptive performance against static strategies.
  </li>
</ol>

<hr>

<h2>🎬 Demo</h2>

<p><strong>Video Demo Available:</strong><br>
(Attached in LinkedIn Post / GitHub Release)</p>

<p>Watch the walkthrough showing regime detection, model training, and live trading simulation!</p>

<hr>

<h2>📊 Results</h2>

<ul>
  <li>Successfully detects and adapts to changing market regimes.</li>
  <li>Demonstrates better risk-adjusted returns compared to static models.</li>
  <li>Training done fully on CPU — no GPU dependency.</li>
</ul>

<hr>

<h2>🚀 Future Improvements</h2>

<ul>
  <li>Integrate more sophisticated regime signals (e.g., macroeconomic indicators).</li>
  <li>Expand to multi-asset portfolio management.</li>
  <li>Deploy live with real-time streaming data.</li>
</ul>

<hr>

<h2>🤝 Acknowledgments</h2>

<p>Huge thanks to the open-source communities in <strong>Reinforcement Learning</strong>, <strong>Quantitative Finance</strong>, and <strong>Machine Learning</strong> — without which this project would not be possible.</p>

</body>
</html>
