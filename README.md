# Power Consumption Forecasting
Final Project for BANA 4090 at UC's Linder College of Business, completed alongside Ethan Chaney and Keegean Mcgorry

## Overview
This project forecasts residential energy consumption using machine learning and time series methods. Built as a final group project for the Forecasting & Risk Analytics course, the model supports infrastructure planning and demand forecasting for utilities.

## Key Questions
- How accurately can we predict monthly energy usage using historical data?
- Which forecasting model performs best: ARIMA, Exponential Smoothing, or CNN?
- How can risk and model performance be communicated to decision-makers?

## Key Insights
- Granularity had a major impact: moving from daily to monthly data improved R² from negative to 0.74.
- CNN1D performed best in fitting peaks/valleys but ARIMA remained strong for interpretability and consistency.
- Model tuning and proper normalization were critical in reducing overfitting and improving accuracy.

## Tools Used
- Python (pandas, scikit-learn, statsmodels, TensorFlow/Keras)
- Time Series Modeling: ARIMA, Exponential Smoothing
- Deep Learning: CNN1D
- Evaluation Metrics: MAE, MSE, R²
- Visualization: Matplotlib

## Deliverables
- `Group14_FinalProject_BANA4090.ipynb`: Full model development, tuning, and evaluation process
-    **Requires Power_Consumption.csv** to be in the same folder as it is executed.

## Contributors
- **Ryan Morris** – Led project coordination, developed CNN1D model, handled data wrangling and error analysis, and structured initial code framework.

-**Ethan Chaney** – Built Exponential Smoothing model; contributed to exploratory data analysis and visualizations.

-**Keegean Mcgorry** – Built ARIMA model; contributed to exploratory data analysis and visualizations.

## Notes
Created as the final project for BANA 4090: Forecasting and Risk Analytics. The focus was on presenting practical insights from predictive models to a business audience.
