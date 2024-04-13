Monthly Time Series Forecasting for Industry
This repository contains a Python-based time series forecasting model for analyzing monthly production data in various industries. The algorithm leverages different techniques such as ARIMA, SARIMA, Linear Regression, Exponential Smoothing, and Seasonal Decomposition to model and predict future production trends.

Features
Model Calibration: Calibrate models based on historical data to understand behaviors and patterns.
Error Calculation: Evaluate the accuracy of models using past data.
Forecasting: Generate future predictions based on trained models.
Visualization: Plot the results to provide clear insights into the trends and forecasts.
Requirements
To run the scripts, you need the following libraries:

pandas
numpy
matplotlib
seaborn
scipy
statsmodels
sklearn
pmdarima
asyncio
datetime
missingno
Make sure all dependencies are installed using pip:

bash
Copy code
pip install pandas numpy matplotlib seaborn scipy statsmodels sklearn pmdarima asyncio datetime missingno
Data Structure
The data should be in an Excel file named BG_Consolidado.xlsx with specific columns as required by the script. Ensure the data includes columns for dates, keys, and values.

Usage
Calibration and Validation Setup:

Adjust the parameters under the 'Setup' section to match the timeframe and data specifics of your dataset.
Ensure the timeframes for calibration and validation match your data availability.
Running the Forecast:

Execute the Python scripts to perform model training and predictions.
View plots and metrics for analysis.
Output:

The forecasts are saved in an Excel file and various plots are generated for visualization.

Contributing
Contributions to this project are welcome. Please fork the repository and submit a pull request.

License
This project is licensed under the MIT License - see the LICENSE.md file for details.
