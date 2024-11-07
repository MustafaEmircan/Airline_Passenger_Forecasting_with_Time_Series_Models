# Airline Passenger Forecasting with Time Series Models

## Project Overview
This project involves forecasting airline passenger numbers using various time series models, ultimately selecting **Holt-Winters Triple Exponential Smoothing** for the final model. The process includes implementing and evaluating multiple models to identify the best-performing approach for accurate forecasting.

### Models Explored
- **Simple Exponential Smoothing**: Initial model to capture general trend.
- **Double Exponential Smoothing**: Adds trend adjustment for better accuracy.
- **Triple Exponential Smoothing (Holt-Winters)**: Incorporates seasonality for more refined forecasting.
- **ARIMA**: A popular model for time series analysis, accounting for autoregressive and moving average components.
- **SARIMA**: Extends ARIMA by adding seasonal components, useful for periodic data patterns.

After evaluating each model, **Holt-Winters Triple Exponential Smoothing** was chosen for the final forecasting model.

### Forecasting & Visualization
The final model forecasts the next **12 months** of airline passenger data, with results visualized alongside historical data to clearly illustrate the model’s predictive performance.

### Project Structure
- **Model Evaluation**: Comparison of multiple time series models.
- **Final Model**: Application of Holt-Winters to produce the final forecast.
- **Visualization**: Graph of forecasted values for the next year with past data.

## Getting Started
To run the project:
1. Install necessary packages: `pip install -r requirements.txt`.
2. Run the `airline_passengers.py` script to generate forecasts and visualizations.

## Usage
This project serves as an example for implementing and evaluating various time series forecasting methods, providing a basis for selecting the best model for similar projects.

---

### License
This project is licensed under the MIT License.
