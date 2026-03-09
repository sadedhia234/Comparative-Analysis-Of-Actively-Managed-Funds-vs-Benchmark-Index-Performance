**Comparative Analysis: Active Managed Funds vs. Benchmark Index**

This project provides a comprehensive framework to evaluate and compare the performance, risk metrics, and structural differences between actively managed funds and passive benchmark index funds. Using Fidelity Contrafund (FCNTX) as the active representative and Vanguard S&P 500 ETF (VOO) as the benchmark, the analysis utilizes Python-based data visualization and financial modeling to determine where active managers add value.

📊 Project Overview
The core objective is to determine if active management justifies its higher fees through outperformance (Alpha) or if a passive strategy offers better risk-adjusted returns.
Key Performance Metrics :
  - Annualized Returns: Comparing historical growth over 1-year and 10-year horizons.
  - Expense Ratios: Analyzing the impact of FCNTX’s higher fees (0.39%) versus VOO’s low-cost structure (0.03%).
  - Risk-Adjusted Returns: Evaluating performance using the Sharpe Ratio for passive funds and the Information Ratio for active management.
  - Volatility: Measuring risk through Standard Deviation.
  - Brinson Attribution: Breaking down active return into Asset Allocation and Security Selection

🛠️ Tech Stack & Methodology
This project is built entirely in Python, leveraging industry-standard libraries for financial data engineering and visualization.
  - Data Fetching: yfinance is used to pull real-time market data and historical price action.
  - Data Manipulation: Pandas for cleaning data, merging sector-wise returns, and calculating percentage changes.
  - Visualization: Plotly and Matplotlib for interactive line charts, sector breakdown donuts, and top-holding distributions.
  - Dashboarding: Dash provides a web-based interface for dynamic fund comparison.

📈 Key Findings
 - Short-Term Outperformance: At the 1-year mark, FCNTX outperformed the benchmark, generating an active return of 5.11%.
 - Long-Term Consistency: Over a 10-year horizon, the active fund struggled to consistently beat the benchmark index.
 - Source of Alpha: Analysis indicates that the active manager demonstrated poor Asset Allocation but strong Security Selection within specific sectors.
 - Risk Factor: The Information Ratio (IR) for the active fund (3.60) was higher than the benchmark's Sharpe Ratio (1.51), suggesting superior active management performance    relative to the additional risk taken.

🚀 How to Run the Dashboard
1. Install dependencies: pip install dash yfinance pandas plotly requests beautifulsoup4 openpyxl
2. Run the application: python Dashboard_dash.py
3. Access the web interface: Open your browser and navigate to: http://127.0.0.1:8050/

Author: Saloni Dedhia Project: Financial Modeling Final Project
