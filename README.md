# Momentum-Top-2-Selector-Multi-Asset-

**Description**  
Cross-sectional momentum strategy that computes 20-day compounded returns (shifted by 1 day to avoid look-ahead) across a flexible universe (sectors, ETFs, stocks, crypto, or all). Each day it ranks assets by momentum, goes long the top 2 tickers equally, and compares performance to a benchmark (SPY or BTC-USD). Optional toggle restricts the universe to long-term underperformers vs the benchmark.

In simple terms: it finds the strongest recent trends in your chosen universe, buys the two current leaders each day, and tracks how that performs vs just holding SPY/BTC.

**Sample performance (UNIVERSE_MODE="ALL", L=20, top_k=2)**  
- Strategy total return: **+2347.69%**  
- Strategy CAGR: **54.88%**  
- Strategy Sharpe (rf=0): **1.22**  
- Strategy max drawdown: **-40.86%**  

- SPY total return: **+167.85%**  
- SPY CAGR: **14.43%**  
- SPY Sharpe (rf=0): **0.78**  
- SPY max drawdown: **-33.72%**


<img width="989" height="590" alt="image" src="https://github.com/user-attachments/assets/840caca9-e8cf-43c0-926c-68b875b01d2d" />
