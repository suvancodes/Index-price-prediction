# Index Price Prediction

## Project Overview

This repository focuses on **predicting index prices** (such as stock or financial indices) using machine learning and time series models. It covers the full pipeline — from data collection and preprocessing to model training, evaluation, and visualization. The goal is to forecast index trends based on historical data and identify which models perform best.

## Dataset Description

The dataset contains historical index data including columns such as `Date`, `Open`, `High`, `Low`, `Close`, and `Volume`. It is used to train regression and forecasting models that predict future index values.

## Key Steps & Methods

1. **Exploratory Data Analysis (EDA)**

   * Visualized index trends, moving averages, and volatility.
   * Checked for missing values, outliers, and data consistency.

2. **Preprocessing & Feature Engineering**

   * Cleaned missing and inconsistent data.
   * Created lag features and rolling averages to capture temporal patterns.
   * Applied feature scaling where necessary.

3. **Modeling**

   * Implemented baseline models like **Linear Regression, Ridge, and Lasso**.
   * Experimented with **ARIMA / Prophet / XGBoost** for time series forecasting.
   * Used cross-validation and grid search for tuning model hyperparameters.

4. **Evaluation**

   * Metrics: **RMSE, MAE, R², and MAPE**.
   * Visualized predicted vs. actual values to assess performance.

5. **Results**

   * Models achieved consistent prediction accuracy across test data.
   * Ridge and XGBoost performed best with balanced bias–variance tradeoff.

## How to Run

1. **Clone the repository**

   ```bash
   git clone https://github.com/suvancodes/Index-price-prediction.git
   cd Index-price-prediction
   ```

2. **Install dependencies**

   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn statsmodels xgboost prophet
   ```

3. **Run notebooks**

   ```bash
   jupyter notebook
   ```

   * Open and execute the notebook step by step.

## Future Improvements

* Incorporate external economic indicators and news sentiment.
* Implement deep learning models like **LSTM** or **Transformer** for improved forecasting.
* Create a **Flask or Streamlit web app** for real-time predictions.

## License

MIT License

## Contact

For questions or contributions, open an issue or contact the repository owner:
**GitHub:** [@suvancodes](https://github.com/suvancodes)
