# Value Investing Algorithm

A quantitative value investing screener that ranks securities using fundamental analysis ratios, identifying the top 10 most undervalued stocks from a given universe.

## Overview

This algorithm implements a multi-factor value scoring system using five key fundamental ratios. Each security is scored and ranked across all metrics to produce a composite value score, surfacing the most attractively valued opportunities.

## Methodology

Securities are evaluated using:
- **Price-to-Earnings (P/E)** ratio
- **Price-to-Book (P/B)** ratio
- **Price-to-Sales (P/S)** ratio
- **EV/EBITDA** (Enterprise Value to EBITDA)
- **EV/GP** (Enterprise Value to Gross Profit)

Each ratio is percentile-ranked across the universe, and a composite score selects the top 10 undervalued securities.

## Tools & Libraries

- **Python** (pandas, NumPy, yfinance, SciPy)
- Fundamental data via Yahoo Finance API
- Statistical ranking and percentile scoring

## Key Outputs

- Ranked list of top 10 undervalued securities
- Composite value scores across all five metrics
- Recommended position sizes based on portfolio value

## Module

Personal Project

## Usage

*Jupyter notebook with full implementation and walkthrough coming soon.*
