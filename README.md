# Mean Variance Optimization using Monte Carlo Simulation

## Overview

This project implements Mean Variance Optimization (MVO) using Monte Carlo simulation, a technique commonly used in modern portfolio theory. The MVO is a mathematical approach to construct an efficient portfolio that maximizes expected return for a given level of risk, or minimizes risk for a given level of expected return. The Monte Carlo simulation is used to generate a large number of random portfolios and estimate their risk and return characteristics.

This project utilizes Python as the main programming language and leverages various libraries such as NumPy, Pandas, and Matplotlib to perform the calculations, data manipulation, and visualization.

## Features

The key features of this project are:

- Mean Variance Optimization: The project implements the MVO framework, which involves calculating portfolio risk and return, solving the optimization problem to find the efficient frontier, and visualizing the results.

- Monte Carlo Simulation: The project uses Monte Carlo simulation to generate a large number of random portfolios with different asset weightings to estimate the risk and return characteristics of the portfolios.

- Data Retrieval and Manipulation: The project retrieves historical financial data, such as stock prices or returns, and performs data manipulation tasks such as cleaning, aggregation, and calculation of portfolio risk and return.

- Visualization: The project visualizes the efficient frontier, which represents the set of portfolios that offer the highest expected return for a given level of risk, using Matplotlib, a popular data visualization library in Python.

## Usage

The following steps outline how to use this project:

1. Install Dependencies: Make sure you have Python 3.x installed on your system. Install the necessary libraries such as NumPy, Pandas, and Matplotlib by running the following command in your terminal or command prompt:

   ```
   pip install numpy pandas matplotlib yfinance
   ```

2. Data Retrieval: Retrieve historical financial data, such as stock prices or returns, that you want to use for portfolio optimization. In this code I retreived the financial data from yfinance.

3. Data Manipulation: Perform data manipulation tasks such as cleaning, aggregation, and calculation of portfolio risk and return using the provided functions in the project code or implement your own functions as needed.

4. Monte Carlo Simulation: Use the Monte Carlo simulation function in the project code to generate a large number of random portfolios with different asset weightings. Specify the number of portfolios to generate and the range of asset weights to consider.

5. Mean Variance Optimization: Use the calculated portfolio risk and return characteristics from the Monte Carlo simulation to solve the MVO optimization problem and find the efficient frontier. Visualize the results using the provided plotting functions in the project code or customize the plots as desired.

6. Interpret Results: Analyze the efficient frontier to make informed decisions about the optimal asset allocation that balances risk and return based on your investment objectives.

# Interpret the results and make investment decisions
```
