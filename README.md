# Energy-Consumption-Regression-Model.
End-to-end time-series forecasting pipeline with engineered temporal features, Ridge regression, and coefficient stability analysis.
Energy Consumption Forecasting
Overview

This project builds a time-series aware regression model to predict the next 24-hour average energy consumption using historical usage and environmental data.

The focus of this project is on:

Advanced feature engineering

Time-series validation

Model interpretability

Coefficient stability analysis

Methodology
Data Processing

Standardized column naming

Datetime parsing

Encoding categorical features

Chronological sorting

Feature Engineering

Rolling statistics (mean, std)

Lagged percent change features

Cyclical encoding (sin/cos)

Expanding statistics

Log transformation

Modeling

Ridge regression

TimeSeriesSplit cross-validation

StandardScaler normalization

Evaluation using MSE and R²

Results

Average R²: 0.88

Stable coefficients across folds

Rolling average and lag features were the strongest predictors

Key Insights

Recent consumption trends are highly predictive of short-term future demand. Time-aware validation prevents leakage and ensures realistic performance estimation.

Tech Stack

Python

Pandas

NumPy

Scikit-learn

Matplotlib
