# Predicting Exxon Stock Price Based on Oil Price Using Linear Regression

## Overview

This project applies a **supervised machine learning approach**—specifically **linear regression**—to model and predict **ExxonMobil's (XOM)** stock price based on the global **crude oil price per barrel**. By analyzing historical price movements correlation, this project aims to quantify the relationship between oil prices and Exxon’s stock, providing insights into how sensitive the company’s valuation is to commodity fluctuations. This serves as a foundation for energy sector modeling and short-term trading signals.

## Objectives

* Predict Exxon stock price using oil price data.
* Quantify the linear relationship between crude oil prices and Exxon’s market valuation.
* Provide a simple, interpretable model for investors to gauge Exxon’s exposure to oil price volatility.

## Why Linear Regression?

Linear regression is chosen for its **simplicity, interpretability**, and suitability for modeling **direct relationships** between two continuous variables. In this case, it helps estimate the directional impact of oil price changes on Exxon’s stock price—crucial information for both retail and institutional investors in the energy sector.

## Dataset

Daily closing stock and oil price from Mar 2014 - Mar 2019

* **Data Sources**:

  * Crude Oil (WTI) Price per Barrel: U.S. Energy Information Administration (EIA), Yahoo Finance
  * ExxonMobil Stock Price: Yahoo Finance

### Features Used:

* `crude_oil_price` (USD/barrel)
* `exxon_stock_price` (USD/share)

## Libraries

* NumPy
* Pandas
* Scikit-learn
* scipy
* Matplotlib

## Limitations

While this linear regression model captures the general trend between oil prices and Exxon’s stock, it does **not account for**:

* Broader market sentiment
* Company-specific events (earnings reports, lawsuits, etc.)
* Other macroeconomic variables (interest rates, inflation, geopolitical events)
* Non-linear effects or lagged impacts

The model serves as a **first-step tool** for price sensitivity analysis and could be improved with multivariate or time series models (e.g., ARIMA, LSTM).

## Use Case

### Hedging and Exposure Analysis

An energy-focused hedge fund wants to estimate how Exxon’s stock might react to future changes in oil prices. Using this linear regression model, they determine that for every \$1 increase in oil price, Exxon’s stock price tends to rise by approximately \$0.85.

They use this model to:

* Construct hedging strategies
* Forecast short-term price movements
* Monitor oil price news for early trading signals

## Conclusion

This project demonstrates how a simple **linear regression model** can reveal actionable relationships between commodity prices and stock performance. Though basic, it provides a **data-driven approach to risk analysis** and **market forecasting**, especially relevant for companies like ExxonMobil, whose fortunes are closely tied to crude oil markets.

Future work can include:

* Incorporating multiple oil benchmarks (Brent, WTI)
* Adding lagged features or volume data
* Expanding to other oil-dependent companies

**Key Value:**
A lightweight predictive tool that helps **quantify price exposure**, enabling faster, smarter decision-making for investors and energy analysts.
