# LPG Price Forecasting Using Machine Learning and Time Series Models

This project develops a predictive framework for forecasting Liquefied Petroleum Gas (LPG) prices using a combination of statistical time-series models and machine learning techniques. The objective is to evaluate how different modelling approaches perform in forecasting commodity price movements and to compare their predictive accuracy.

## Models Implemented

The project explores multiple forecasting approaches:

* **SARIMAX** for classical statistical time-series modelling
* **Prophet** for trend and seasonality decomposition
* **Vector Autoregression (VAR)** for multivariate time-series relationships
* **XGBoost** for gradient-boosted machine learning predictions
* **LSTM Neural Networks** for deep learning based sequential modelling

## Ensemble Modelling

Predictions from multiple models are combined using a **ridge stacking ensemble**, improving forecasting robustness and reducing model-specific bias.

## Model Explainability

To interpret model behaviour, **SHAP (SHapley Additive Explanations)** is used to analyze feature importance and understand the contribution of different variables to price predictions.

## Evaluation and Backtesting

Models are evaluated using forecast error analysis and backtesting procedures to assess predictive performance on unseen data. Error distributions and diagnostic plots are generated to validate model reliability.

## Outputs

The project produces:

* Forecast plots comparing model predictions
* Feature importance and explainability visualisations
* Residual diagnostics and error distributions
* Backtesting summaries and prediction datasets

## Technologies Used

* Python
* Pandas / NumPy
* Scikit-learn
* XGBoost
* TensorFlow / Keras (LSTM)
* Statsmodels
* Prophet
* SHAP
* Matplotlib / Seaborn

## Purpose

This project demonstrates the application of **hybrid machine learning and econometric methods for commodity price forecasting**, highlighting the strengths and limitations of different modelling techniques in real-world financial and energy market prediction tasks.
