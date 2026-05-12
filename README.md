# Evolutionary Optimization of an Intraday Strategy: A GA Approach to the ORB

This repository contains the models, data, and experimental results for my Bachelor's Degree Final Project (TFG) at **Universidad Autónoma de Madrid (UAM)**.

## Project Overview
This research evaluates the portability and performance of an evolutionary **Opening Range Breakout (ORB)** strategy within the U.S. equity market, specifically testing the **CME E-mini S&P 400 MidCap (EMD)** futures. 

By applying **Genetic Algorithms (GA)** and **Walk-Forward Analysis**, the project explores how a trading system can dynamically adapt its parameters to handle market noise and volatility. The study reveals a significant shift from traditional fixed stop-losses to dynamic, retracement-based profit conservation (RDD).

## Repository Structure
- **`/SQX_Models`**: Includes the native `.sqx` files. These files contain the full strategy logic and optimized parameters, ready to be loaded into **StrategyQuant X**.
- **`/Data`**: Sample of the historical data (2009-2018) utilized during the 60/30 day Walk-Forward optimization cycles.
- **`/Other languages`**: You can download the strategy code for MetaTrader 4, 5 and in java code, as well as a simple pseudocode.

## Author
**Jorge Moncada Gutiérrez** Bachelor in Economics and Finance  
*Universidad Autónoma de Madrid, 2026*
