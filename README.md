
# SARIMA-Based Forecasting of Antidiabetic Drug Prescriptions in Australia

## Project Overview

The project I am working on involves the use of the SARIMA model to forecast the number of antidiabetic drug prescriptions in Australia from 1991 to 2008. This project comes from the book “Time Series Forecasting in Python” by Marco Peixeiro. The data has been recorded by the Australian Health Insurance Commission and includes monthly records over 17 years. The purpose is to use the SARIMA model to predict the number of prescriptions in the future. The latter may be used by production planning specialists to undertake the necessary actions to make the supply of these medications meet the demand.

## Objective

The primary aim of this project is to forecast future prescription numbers using the SARIMA model. Such forecasts may be used to plan the production and distribution of antidiabetic medications, allowing supply to be distributed effectively and effectively matched to demand.

## Dataset

- **Source**: Australian Health Insurance Commission
- **Time Period**: 1991 to 2008
- **Frequency**: Monthly
- **Data Description**: The dataset includes monthly counts of antidiabetic drug prescriptions.

## Methodology

1. **Data Exploration**: Initial exploration and visualization of the time series data to understand the trends and seasonality.
2. **Model Selection**: Application of the SARIMA model, which is suitable for time series data with both trend and seasonal components.
3. **Model Training**: Fitting the SARIMA model to the historical data.
4. **Forecasting**: Using the trained model to predict future prescription numbers.
5. **Model Evaluation**: Assessing the model’s accuracy and making adjustments as necessary.

## Key Files

- `AusAntidiabeticDrug.ipynb`: The Jupyter notebook containing the entire workflow, including data loading, preprocessing, model development, and forecasting.

## Requirements

To run the code in this project, you will need the following Python libraries:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `statsmodels`
- `scikit-learn`

You can install these libraries using pip:

```bash
pip install pandas numpy matplotlib seaborn statsmodels scikit-learn
```

## Results

The final SARIMA model provides forecasts for the number of antidiabetic drug prescriptions in Australia. The results highlight the model’s ability to capture both the seasonal patterns and long-term trends in the data.

## Acknowledgements

This project is based on the capstone project in *"Time Series Forecasting in Python"* by Marco Peixeiro. The dataset was sourced from the Australian Health Insurance Commission as provided in the book.
