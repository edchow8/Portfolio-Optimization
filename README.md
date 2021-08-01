# Portfolio Optimization Project

## Overview

In this project, we will build an investment portfolio using Ray Dalio's All Weather Portfolio (AWP) as a benchmark, and optimize it using Markowitz's Modern Portfolio Theory (MPT) and Wiiliam Sharpe's Sharpe Ratio. Our goal is to find the alternate combination of the AWP that minimize risk and maximize returns, and compare it to the original weightings suggested by Ray Dalio.

The "All Weather Portfolio" (AWP) concept originated from Ray Dalio, founder of Bridgewater Associates, the world's largest hedge fund. As the name suggest, this portfolio is designed to weather any storm in the market, and should be easy to manage for an average investor. Below is the allocation of the AWP, along with the ETF's that will be used to replicate each category of the AWP:

- 30% US stocks ('SPY' - SPDR S&P500 ETF Trust)
- 40% Long-term bonds ('TLT' - iShares 20 Plus Year Treasury Bond ETF)
 - 15% Intermediate-term bonds ('IEI' - iShares 3-7 Year Treasury Bond ETF)
- 7.5% Commodities ('DBC' - Invesco DB Commodity Index Tracking Fund)
- 7.5% Gold ('GLD' - SPDR Gold Trust)

Markowitz's Modern Portfolio Theory states that risk-averse investors, given a set of portfolios that provide the same expected return, will favor the one with the minimum level of risk. All individual assets' risks and returns have great impacts in the portofolio's profile, which highlights the importance of diversification in assets with little (or negative) correlation in a portfolio.

When every possible combination of the selected assets is plotted in a graph that compares returns vs. volatility (risk), the group of possible portfolio usually forms a bullet shape. The upper left boundary of the bullet shape is also known as the "efficient frontier", which shows the set of portfolios with the highest expected returns and the minimum level of risk. All the portfolios beneath the efficient frontier as deemed as "inefficient".

The last concept that we will use for this project is the Sharpe Ratio (SR). The ratio measures the risk-adjusted returns of a portfolio by substracting the risk-free rate of return from the expected return of a portfolio, and dividing it by the volatility of the portfolio. A higher ratio means higher returns per unit of volatility, hence, the better. A SR above 1 is considered good for investors. We will assume a 0% risk-free rate for this exercise.

In summary, we will build the AWP using its weightings suggested by Ray Dalio, use the MPT and efficient frontier to find a set of "efficient" portfolios, and find the one with the highest Sharpe ratio. This will be our most "optimal" portfolio, and we will compare the weightings and performance of the original AWP and the optimized AWP. 

**Will the optimized AWP perform better that the original AWP?**

## How to download and review my work
You can download the ".ipynb" file from this repository and open it with Jupyter Notebook. This way you'll be able to customize and edit the code as you wish.

If you don't have Jupyter Notebook installed on your computer, you can either:
- Dowload/install the Anaconda package (https://www.anaconda.com/products/individual), which includes the Jupyter Notebook, or
- Click on the ""Portfolio-Optimization-Project.ipynb" file, and you'll be taken into "view mode" on GitHub. You won't be able to edit the code, but you'll be able to view the file as if you were in Jupyter Notebook.

In case you have any questions
Please feel free to reach out to me using my e-mail address below if you have any questions regarding this work.

E-mail: edchow01@gmail.com
