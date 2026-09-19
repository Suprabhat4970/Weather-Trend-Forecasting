# Weather Trend Forecasting

## Project Overview

This project analyzes global weather data and explores temperature trends using Python. It includes data cleaning, exploratory data analysis, visualizations, basic forecasting, and potential anomaly detection.

## Dataset

The project uses the Global Weather Repository dataset.

The dataset includes country, location, latitude, longitude, date/time, temperature, and weather condition information.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

## Project Features

* Data cleaning and preprocessing
* Exploratory data analysis (EDA)
* Temperature distribution and weather-condition visualizations
* Daily temperature analysis for Suva, Fiji
* Baseline temperature forecasting
* Rolling one-step-ahead forecast evaluation
* Potential temperature anomaly detection using the IQR method
* Country and location temperature comparisons

## How to Run

1. Clone or download this repository.

2. Install the required libraries:

   `pip install -r requirements.txt`

3. Open the Jupyter Notebook:

   `jupyter notebook`

4. Open `notebooks/weather_analysis.ipynb`.

## Important Notes

* Missing daily temperature values for the selected location were interpolated for analysis.
* A suspicious temperature value above 60°C was excluded from the cleaned dataset; the original data was retained.
* Forecasting results are exploratory and depend on the selected location and evaluation method.
* The dataset covers a limited period and should not be treated as long-term climate data.

## Author

Suprabhat Jana
