# 📊 ETF Analysis with Python & Monte Carlo Simulation

## Overview
This project analyzes a selection of **Vanguard ETFs** to explore how a $10,000 investment could be allocated for both **growth** and **risk management**.  

The analysis uses **Python, yfinance, and Monte Carlo simulation** to provide insights into returns, volatility, and potential future outcomes.

---

## Problem Statement
**Scenario:**  
I have $10,000 to invest in Vanguard ETFs. After conducting initial research, I shortlisted several ETFs to analyze further.  

**Goal:**  
Select a diversified mix of ETFs that balances **strong growth potential** with **minimized risk exposure**.

---

## Approach

1. **Data Collection**  
   - Pulled 5 years of ETF price data from Yahoo Finance
2. **Statistical Analysis**  
   - Annualized average returns  
   - Annualized volatility  
   - Skewness and kurtosis (distribution shape)  
   - Minimum and maximum returns  

3. **Monte Carlo Simulation**  
   - Simulated 1,000 possible paths for each ETF  
   - Modeled 252 trading days (1 year)  
   - Estimated probability distributions of final portfolio values  

4. **Visualization**  
   - Annualized returns vs. volatility  
   - Cumulative returns per ETF  
   - Price trends  
   - Monte Carlo outcome distributions  

---

## Results & Insights
- **Growth ETFs (VUG, VGT)**  
  - Higher potential returns  
  - Higher volatility (more risk)  

- **Broad Market ETFs (VTI)**  
  - Lower returns than growth ETFs  
  - More stability and diversification  

---

## Tech Stack
- Python 
- [pandas](https://pandas.pydata.org/) – data manipulation  
- [numpy](https://numpy.org/) – numerical calculations  
- [yfinance](https://github.com/ranaroussi/yfinance) – financial data  
- [matplotlib](https://matplotlib.org/) & [plotly](https://plotly.com/python/) – visualizations  
- [scipy](https://scipy.org/) – statistical measures  

