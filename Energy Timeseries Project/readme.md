Project: SARIMA Model for Forecasting U.S. Energy Importation and Exportation

Overview
This project involves building and evaluating Seasonal Autoregressive Integrated Moving Average (SARIMA) models to forecast primary energy imports and exports in the United States. The analysis leverages historical energy data to develop reliable predictive models that can aid in strategic planning and policy-making.

Files
sarima_model_final.ipynb: The Jupyter notebook containing the complete analysis, including data preprocessing, model selection, fitting, residual diagnostics, and forecasting.
US_government_energy_data.csv: The dataset used for the analysis, containing historical data on U.S. energy imports and exports.
Dependencies

Ensure the following Python libraries are installed:

pandas
numpy
matplotlib
statsmodels
scipy


Data Preparation:

Load the dataset and preprocess it by converting the date column to datetime format and setting it as the index.
Filter the data to focus on primary energy imports and exports, and separate them into different DataFrames.
Stationarity Check:

Use the Augmented Dickey-Fuller (ADF) test to check for stationarity.
Apply differencing to make the data stationary if necessary.
Model Selection:

Perform a grid search to identify the best SARIMA model parameters based on AIC and BIC.
Model Fitting and Forecasting:

Fit the SARIMA models to both imports and exports data.
Forecast future values for the next 36 months and visualize the results.
Residual Diagnostics:

Conduct residual diagnostics to ensure the models' validity by checking for normality and autocorrelation in the residuals.
Results
The SARIMA models successfully forecast future values of U.S. primary energy imports and exports, providing valuable insights for energy planning and policy-making. The models demonstrated good fit and predictive accuracy, with well-specified residuals indicating robustness.

Conclusion
This project offers a comprehensive approach to time series forecasting using SARIMA models, emphasizing the importance of thorough data preprocessing, model selection, and residual diagnostics. The results can inform strategic decisions in the U.S. energy sector, contributing to energy security and sustainable resource management.

Contact
For any questions or further information, please contact:

Name: James Paul
Email: jamespaul69450@gmail.com
LinkedIn: [James Paul](https://www.linkedin.com/in/james-paul-business-analyst/)
GitHub: JamesP94