
# Portfolio Optimization

This project demonstrates how to apply portfolio optimization techniques using historical stock data to find the optimal asset allocation that maximizes returns while minimizing risk.

## 📚 Description

- Downloads and processes historical stock data.
- Calculates expected returns, standard deviation, and covariance of returns.
- Optimizes the portfolio using Monte Carlo simulation and the Efficient Frontier.

## 🧰 Libraries Used

- NumPy  
- Pandas  
- Matplotlib  
- yfinance  
- PyPortfolioOpt  

## 🛠️ Features

- Automated data retrieval for multiple stocks using `yfinance`.  
- Visualization of Efficient Frontier and optimal portfolio points.  
- Calculation of Sharpe ratio and maximum return portfolio.  
- Weights normalization and clean tabular output.  

## 🚀 How to Run

1. Clone this repository.  
2. Install dependencies from `requirements.txt`.  
3. Run the notebook using Jupyter.

```bash
pip install -r requirements.txt
jupyter notebook "Portfolio Optimization.ipynb"
```

## 📁 File Structure

- `Portfolio Optimization.ipynb` - Main notebook with all code.  
- `requirements.txt` - Python libraries needed for execution.  

## 🔮 Future Enhancements

- Incorporate different risk models (e.g., CVaR).  
- Add support for real-time data refresh.  
- Deploy as a web app using Streamlit or Dash.  

## 📄 License

This project is licensed under the MIT License.

