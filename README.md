# Portfolio Optimization using Machine Learning and Monte Carlo Simulation

A quantitative finance project focused on optimizing investment portfolios using machine learning techniques, Monte Carlo simulation, and modern portfolio theory.

This project analyzes portfolio risk and return characteristics by simulating thousands of possible portfolio combinations and identifying optimal asset allocations based on performance metrics such as expected return, volatility, and Sharpe Ratio.

---

## Project Objective

 

If an investor has money to invest across multiple stocks, the big question is:

 

> “How much money should be allocated to each stock to get the best risk-return balance?”

  

The objective of this project is to develop an optimized investment portfolio using quantitative finance techniques and machine learning-driven analysis. The project applies Monte Carlo simulation to generate multiple portfolio allocations and evaluate their risk-return trade-offs over time.

By combining statistical analysis, financial modeling, and portfolio optimization techniques, the project aims to identify efficient portfolios that maximize returns while minimizing investment risk.

---

## Key Features

* Portfolio return and risk analysis
* Monte Carlo portfolio simulation
* Sharpe Ratio optimization
* Efficient frontier visualization
* Risk-return tradeoff analysis
* Portfolio weight optimization
* Financial data preprocessing
* Data visualization and statistical analysis
* Machine learning-based portfolio evaluation

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* yfinance
* SciPy

---

## Methodology

### Data Collection

Historical stock price data is collected from yfinance and processed for portfolio analysis and simulation.

 

**Stocks Used in the Portfolio**

The portfolio optimization analysis was conducted using historical stock price data from major Indian companies listed on the National Stock Exchange (NSE). The selected stocks represent diversified sectors of the Indian economy, including finance, energy, metals, infrastructure, FMCG, and industrial manufacturing.

The following stocks were included in the portfolio simulation:

* Bajaj Finserv (`BAJAJFINSV.NS`)
* Bharat Petroleum Corporation Limited (`BPCL.NS`)
* Coal India (`COALINDIA.NS`)
* Grasim Industries (`GRASIM.NS`)
* Hero MotoCorp (`HEROMOTOCO.NS`)
* JSW Steel (`JSWSTEEL.NS`)
* Larsen & Toubro (`LT.NS`)
* Nestlé India (`NESTLEIND.NS`)
* Power Grid Corporation of India (`POWERGRID.NS`)
* Titan Company (`TITAN.NS`)

  

### Data Preprocessing

Asset returns, volatility, and covariance matrices are calculated to prepare the dataset for optimization.

### Monte Carlo Simulation

Thousands of random portfolio allocations are generated to evaluate possible risk-return combinations.

### Portfolio Optimization

Optimal portfolios are identified using performance metrics such as:

* Maximum Sharpe Ratio
* Minimum Volatility
* Risk-adjusted Return

### Visualization

Risk-return distributions and efficient frontier plots are used to visualize portfolio performance.

---

## Repository Structure

```bash
Portfolio-Optimization-ML-MonteCarlo/
│
├── Portfolio_Optimization.ipynb
├── README.md
└── requirements.txt
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Portfolio-Optimization-ML-MonteCarlo.git
```

Navigate to the project directory:

```bash
cd Portfolio-Optimization-ML-MonteCarlo
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Running the Project

Launch the notebook using Jupyter:

```bash
jupyter notebook
```

Open the notebook file and run the cells sequentially to perform portfolio optimization and simulation analysis.

---

## Key Insights

* Diversification helps reduce portfolio risk.
* Monte Carlo simulation provides a probabilistic view of portfolio outcomes.
* Optimal portfolios can be identified using Sharpe Ratio maximization.
* Risk-return tradeoffs are essential in investment decision-making.

---

## Future Improvements

* Add deep learning-based portfolio prediction
* Integrate real-time market data
* Develop an interactive dashboard
* Compare optimization techniques
* Add Value-at-Risk (VaR) analysis

---

## Author

Ashis Pal

Finance and data analytics enthusiast focused on quantitative finance, forecasting, and investment analysis.

---

## License

This project is licensed under the MIT License.
