
# Time Series Forecasting

## Description
This project demonstrates **time series forecasting** techniques using Python. The notebook includes:
- Data exploration and visualization
- Time series decomposition
- Building and evaluating ARIMA & SARIMAX models for forecasting

## Libraries Used
The following Python libraries are used in this project:
- statsmodels 
- pandas
- seaborn
- sklearn.metrics
- matplotlib

## Steps in the Notebook
1. **Load and Explore the Dataset**: Initial dataset exploration using Seaborn to visualize the data.
2. **Stationarity Check**: Analyze the time series for trends and seasonality, ensuring stationarity for ARIMA modeling.
3. **ARIMA & SARIMAX Models Implementation**: Build, fit, and evaluate ARIMA & SARIMAX models for forecasting future values.
4. **Model Diagnostics**: Perform residual diagnostics to validate model assumptions.
5. **Visualization of Results**: Plot actual vs. predicted values to assess the accuracy of the model.

## How to Use
1. Clone this repository and navigate to the notebook file.
2. Install the required libraries
3. Open the notebook in Jupyter or Google Colab and run the cells sequentially.

## Outputs
The notebook generates:
- ACF and PACF plots for determining ARIMA & SARIMAX parameters.
- Forecasted time series plots compared against actual values.
- Performance metrics like Mean Squared Error (MSE) and Mean Absolute Error (MAE).

## Acknowledgements
This notebook leverages the Seaborn dataset library and Python's statistical modeling tools for demonstrating time series analysis.
