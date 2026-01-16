# CO2_Trend_Forecasting_NASA

## Description
This project uses Machine Learning to forecast the trend of atmospheric CO₂ levels based on the NASA Mauna Loa historical dataset. A simple Linear Regression model is used to predict CO₂ values and estimate the yearly increase.

## Dataset
- Source: [NASA Mauna Loa CO₂ dataset](https://datahub.io/core/co2-ppm/r/co2-mm-mlo.csv)
- Contains: Date, Monthly Interpolated CO₂, Trend CO₂

## Model
- Linear Regression (Scikit-learn)
- The model predicts CO₂ values using the year as a numerical variable.

## Results
- Historical CO₂ trend plot
- Prediction on the test set plot
- 10-year forecast plot
- RMSE calculated for the test set
- Estimated yearly CO₂ increase

## Tools
- Python 3
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Quickstart / Colab
1. Open the notebook `notebook.ipynb` in Google Colab.
2. Make sure to install the dependencies listed in `requirements.txt`.
3. Run all cells to load the dataset, train the model, and visualize results.
4. Observe RMSE, predicted trend, and 10-year forecast plots.

## Notes
- The forecast is based on a simple linear model and shows a general trend.
- All plots
