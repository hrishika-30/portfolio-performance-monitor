# Portfolio Performance Monitor

This project analyzes the performance of a custom equity portfolio versus the NIFTY 50 benchmark. It calculates key return and risk metrics, helping identify underperforming stocks and flagging those with high volatility or drawdowns.

## A. Portfolio Composition

The portfolio consists of 15 Indian stocks across major sectors:

- **Banking**: HDFC Bank, ICICI Bank  
- **IT Services**: Infosys, TCS  
- **FMCG**: Hindustan Unilever, ITC  
- **Auto**: Tata Motors, Maruti  
- **Pharma**: Sun Pharma, Cipla  
- **Capital Goods**: L&T  
- **Energy**: Reliance Industries, NTPC  
- **Consumer Durables**: Titan  
- **Aviation**: IndiGo

Benchmark: **NIFTY 50** (`^NSEI`)  
Timeline: **1 Jan 2024 – Present**

## B. Tools Used

- `Python`
- `yfinance` – Stock data retrieval  
- `pandas`, `numpy` – Data cleaning and calculations  
- `matplotlib` – Visualizations  

## C. Key Analysis Performed

- **Daily & cumulative returns**
- **Equal-weighted portfolio performance**
- **Volatility estimation (standard deviation)**
- **Drawdown analysis (risk flagging)**
- **Export to CSV for BI/dashboard tools**

## D. Files Included

| File | Description |
|------|-------------|
| `portfolio_analysis.ipynb` | Jupyter notebook with full code |
| `daily_returns.csv` | Daily return % for each stock and benchmark |
| `cumulative_returns.csv` | Cumulative return (NAV-style) |
| `drawdown.csv` | Daily drawdown for portfolio and NIFTY 50 |

---

Feel free to fork, extend, or reuse the code for other stock portfolios, benchmarks, or dashboards.
