# LPG Price Forecasting Using Machine Learning

This project develops a forecasting framework for Liquefied Petroleum Gas (LPG) prices using a combination of statistical time-series models, machine learning algorithms, and deep learning techniques. The objective is to compare different modelling approaches and evaluate their ability to predict commodity price movements.

## Models Implemented

* SARIMAX (statistical time-series modelling)
* Prophet (trend and seasonality forecasting)
* Vector Autoregression (VAR) for multivariate time-series relationships
* XGBoost for machine learning-based prediction
* LSTM neural networks for sequential deep learning forecasting

## Ensemble Learning

Predictions from multiple models are combined using a ridge stacking ensemble to improve predictive performance and reduce individual model bias.

## Model Explainability

SHAP (SHapley Additive Explanations) is used to analyse feature importance and interpret model behaviour.

## Evaluation

Models are evaluated using forecast error analysis, residual diagnostics, and backtesting to assess predictive reliability on unseen data.

## Technologies

Python, Pandas, NumPy, Scikit-learn, TensorFlow/Keras, Statsmodels, Prophet, XGBoost, SHAP, Matplotlib.
