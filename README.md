# Portfolio Optimization Using Sharpe Ratio

## Project Overview  
This project focused on optimizing a stock portfolio to maximize the Sharpe Ratio—a key financial metric used to evaluate risk-adjusted returns. Using historical stock data, I developed a function to determine the ideal allocation of capital across multiple equities while enforcing constraints such as long-only positions and total allocation equal to 100%. The simulation highlights how mathematical optimization can inform smarter investing.

**Languages/Tools Used:** Python, NumPy, SciPy, Matplotlib  
**Key Concepts:** Portfolio Optimization, Sharpe Ratio, Risk-Adjusted Return, Financial Modeling, Constraint Solving

---

## Project Objectives
- Implement a portfolio optimizer to compute allocations that maximize Sharpe Ratio  
- Support dynamic input: any number of stocks, date ranges, and allocation constraints  
- Visualize portfolio performance compared to a market benchmark (SPY)

---

## Technical Highlights
- Created `optimize_portfolio()` in `optimization.py` with support for dynamic stock symbols and date ranges  
- Used **SciPy's `minimize`** function with constraints to ensure all allocations are between 0 and 1 and sum to 1.0  
- Tracked portfolio statistics: cumulative return, average daily return, standard deviation, and Sharpe Ratio  
- Compared performance to SPY over a defined date range and charted the results
- Used sample standard deviation per Sharpe Ratio convention  
- Efficient implementation completed each test in under 5 seconds

---

## Value & Learning Outcomes
- Learned to formulate and solve real-world optimization problems using Python  
- Gained experience working with financial time series data and evaluating portfolio metrics  
- Applied statistical analysis to assess performance under constraints  
- Developed clean, parameterized, and scalable Python code for financial modeling  
- Created investor-friendly visualizations to compare optimized portfolios with market benchmarks

---

## Repository Access  
Due to academic policy, the full implementation—including source code, optimization logic, and output charts—is stored in a private GitHub repository. **Access available upon request.**

