# Air Quality Forecast Prediction Using Prophet model

## Project Overview
This project aims to predict air quality levels using machine learning techniques, specifically **forecasting**. The dataset was sourced using the **UCIMLRepo** library, and any missing values in the data were handled effectively.

## Dataset
The air quality dataset is imported using the **UCIMLRepo** library. In the dataset:
- Missing values are tagged with `-200` as described in the dataset description.
- These values are cleaned and replaced with the **mean** of the corresponding columns.

## Data Preprocessing
The steps taken to clean and preprocess the data are as follows:
1. Convert all `-200` values to `NaN`.
2. Replace all `NaN` values with the **mean** of the respective column.

## Forecasting Methodology
The project utilizes the **FBProphet** library for forecasting air quality levels. FBProphet is a forecasting tool developed by Facebook to handle time series data effectively.

## Libraries Used
The following libraries were used in this project:
- `pandas` - For data manipulation and analysis.
- `numpy` - For numerical operations.
- `matplotlib` - For visualizations.
- `ucimlrepo` - To load the dataset.
- `prophet` - For forecasting tasks.
  
## Tasks Performed
The processed dataset enables the following tasks:
1. **Forecasting** - Time series forecasting using FBProphet.
2. **Regression** - The cleaned dataset can also be used for regression tasks.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/SubhanMalik1/air-quality-forecast-prediction.git
   cd air-quality-forecast-prediction
   ```
2. Install the required libraries:
   ```bash
   pip install pandas numpy matplotlib ucimlrepo prophet
   ```
3. Open and run the notebook:
   ```bash
   jupyter notebook Air_Quality_forecast_prediction.ipynb
   ```
