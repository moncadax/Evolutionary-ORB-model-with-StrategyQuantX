# Evolutionary Optimization of an Intraday Strategy: A GA Approach to the ORB

This repository contains the models, code, and experimental data for my Bachelor's Degree Final Project (TFG) at **Universidad Autónoma de Madrid (UAM)**.

## Project Overview
[cite_start]This research evaluates the portability and performance of an evolutionary **Opening Range Breakout (ORB)** strategy within the U.S. equity market, specifically testing the **CME E-mini S&P 400 MidCap (EMD)** futures[cite: 2699]. 

[cite_start]Using **Genetic Algorithms (GA)** and **Walk-Forward Analysis**, the model dynamically optimizes entry thresholds and protective closing mechanisms, shifting from traditional loss-cutting to dynamic profit conservation (RDD)[cite: 2700, 2703].

## Repository Structure
- [cite_start]`/SQX_Models`: Contains the native `.sqx` files created in **StrategyQuant X**[cite: 2788].
- [cite_start]`/Data`: Sample historical data (2009-2018) used for the Walk-Forward optimization[cite: 3062].
- [cite_start]`/Results`: Key performance reports and equity curves of the 6 optimized models[cite: 2941].

## Key Findings
- [cite_start]**Intraday Noise:** The GA systematically rejected hard stop-losses in the U.S. MidCap market due to high volatility[cite: 2701].
- [cite_start]**Profit Conservation:** Risk-adjusted performance (Sharpe Ratio) is maximized through retracement-based take-profit exits (RDD)[cite: 2702].

## Author
**Jorge Moncada Gutiérrez** BSc in Economics and Finance  
[cite_start]Universidad Autónoma de Madrid (2026) [cite: 2693, 2696]
