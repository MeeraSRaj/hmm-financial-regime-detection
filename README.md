# Hidden Markov Models for Financial Regime Detection

A machine learning project that uses Hidden Markov Models (HMMs) to identify hidden market regimes from historical financial data.

## Overview

Financial markets operate in different regimes such as:

-  Bull Market
-   Bear Market
-  Sideways Market

Since these states are not directly observable, an HMM is used to infer them from market indicators such as returns, volatility, and trading volume. :contentReference[oaicite:0]{index=0}

## Features

- Market regime detection using Gaussian HMMs
- Hidden state decoding with the Viterbi Algorithm
- Financial time-series feature engineering
- Regime visualization on price charts
- Model evaluation and interpretation

## Tech Stack

- Python
- NumPy
- Pandas
- hmmlearn
- Matplotlib
- yfinance

## Workflow

```text
Data Collection
      ↓
Feature Engineering
      ↓
HMM Training
      ↓
State Decoding
      ↓
Regime Visualization
      ↓
Analysis
