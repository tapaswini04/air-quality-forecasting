# air-quality-forecasting
Air quality forecasting using Python, exploratory data analysis, and machine learning.
# Air Quality Forecasting Using Machine Learning

## Project Overview

This project analyzes air quality data and develops a machine learning model to forecast carbon monoxide (CO) concentration using historical measurements and time-based features.

## Objective

* Analyze air quality measurements and identify patterns.
* Perform data cleaning and exploratory data analysis (EDA).
* Engineer time-series features.
* Train and evaluate a machine learning model for CO forecasting.

## Technologies Used

* Python
* Pandas and NumPy
* Matplotlib and Seaborn
* Scikit-learn
* Google Colab

## Methodology

1. Load and inspect the dataset.
2. Handle missing values and invalid measurements.
3. Explore pollutant distributions and correlations.
4. Create lag, rolling-average, and time-based features.
5. Train a Random Forest Regression model using a chronological train-test split.
6. Evaluate predictions using MAE, MSE, RMSE, and R².

## Model Evaluation

The model is evaluated on a later portion of the time series to preserve chronological order.

* MAE: [Insert actual result]
* RMSE: [Insert actual result]
* R²: [Insert actual result]

## Key Findings

Add 5–7 findings based on the actual charts and analysis in the notebook.

## Limitations

* Missing and invalid sensor readings may affect the analysis.
* The model uses historical CO measurements and time-based features, not external weather forecasts.
* Performance on future data may differ from performance on the test set.

## Future Improvements

* Incorporate temperature, humidity, and meteorological data.
* Compare Random Forest with other forecasting models.
* Evaluate performance across different forecast horizons.

## Project Files

* `air_quality_forecasting.ipynb` — Data cleaning, EDA, feature engineering, model training, and evaluation.

## Author

Tapaswini P.
B.Tech CSE (Big Data Analytics), SRM Institute of Science and Technology
