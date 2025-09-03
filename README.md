# Stock-Portfolio-Optimization
Project Overview

This project studies the construction of a portfolio composed of major tech stocks (Google, Apple, Facebook/Meta, Amazon, Microsoft) along with the S&P 500 stock index. The objective is to minimize risk while maximizing expected return by applying portfolio management techniques.
The analysis uses Python and Jupyter Notebook to perform volatility, covariance, correlation, and optimization calculations. By exploring diversification benefits, this project helps investors understand how to balance risk and return in a stock portfolio.

Key Concepts Covered

1. Volatility – Measures price fluctuations and investment risk.

2. Expected Return – The average return expected from an asset.

3. Covariance & Correlation – How stocks move together, influencing diversification.

4. Sharpe Ratio – Risk-adjusted performance measure.

5. Beta – Portfolio’s sensitivity to market movements (S&P 500).

6. Efficient Frontier – Identifies optimal portfolios with maximum return for given risk.


Data Collection

1. Historical data of Google, Apple, Facebook (Meta), Amazon, Microsoft, and S&P 500.

2. Fetched using Yahoo Finance API.

Exploratory Data Analysis (EDA)

1. Price and return distributions.

2. Annual and monthly volatility trends.

3. Correlation analysis among stocks and index.

Portfolio Simulation

1. Generated 2,600+ random portfolios with varying weights.

2. Calculated expected returns, standard deviation, and Sharpe ratio.

Portfolio Optimization

1. Simulated 10,000 portfolios using Dirichlet distribution.

      Identified:

            1. Maximum Sharpe Ratio Portfolio

            2. Minimum Volatility Portfolio

CAPM Analysis

1. Calculated Alpha & Beta of portfolio vs S&P 500.

2. Evaluated performance relative to the market benchmark.

Results & Insights

1. Volatility: Meta (Facebook) showed the highest volatility, meaning higher risk compared to others.

2. Correlation: Strong positive correlations were observed between S&P 500 and Microsoft, Amazon, Google, and Apple — suggesting interdependencies.

3. Sharpe Ratio: Microsoft had the highest Sharpe ratio, offering the best risk-adjusted return.

4. Beta: Helped evaluate how much the portfolio is affected by overall market moves.

5. Efficient Portfolios: Identified optimal combinations that reduced overall risk while maintaining attractive returns.

Conclusion

This project highlights the importance of diversification in portfolio management. By analyzing volatility, correlation, and risk-adjusted returns, we can build smarter portfolios that balance risk and reward.
The findings show that optimizing asset weights leads to better performance than equal-weight strategies. Investors can apply these insights to create portfolios aligned with their risk tolerance and return objectives.
