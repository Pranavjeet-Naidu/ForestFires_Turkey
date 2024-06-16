# Forest Fires Time Series Analysis and Forecasting

This project involves analyzing and forecasting forest fire incidents using time series data. The dataset includes information on forest fire occurrences with attributes like acquisition date, brightness, confidence, and more. The goal is to understand the trends and make future predictions using various time series models.

## Project Steps:

### Data Understanding and Preparation:
- Loaded and explored the dataset using pandas to understand its structure and content.
- Converted the acquisition date to a datetime format and extracted year, month, and day.
- Filtered data to include only records from 2016 onwards.
- Handled missing values and identified duplicate records.
- Visualized data using seaborn and matplotlib to gain insights into the distribution and trends.

### Exploratory Data Analysis:
- Plotted the distribution of forest fire incidents over the years and by day/night.
- Created scatter plots and pair plots to analyze relationships between variables.
- Used box plots to visualize the spread of brightness values.

### Time Series Modeling:
- Split the data into training and testing sets.
- Used ACF and PACF plots to determine the optimal parameters for the ARIMA model.
- Conducted a grid search to find the best ARIMA model parameters (p, d, q).
- Fitted the ARIMA model and made future predictions.

### Holt-Winters Exponential Smoothing:
- Created a synthetic time series and fitted a Holt-Winters model.
- Generated and plotted forecasts, comparing them to the observed data.

### Prophet Model:
- Renamed columns to fit the Prophet model requirements.
- Added yearly seasonality and fitted the model to the data.
- Made future predictions and evaluated the model's performance.

### Model Evaluation:
- Evaluated the models using Mean Absolute Error (MAE) and Mean Absolute Percentage Error (MAPE).
- Compared the forecasted values to the actual values to assess accuracy.

## Libraries Used:
- pandas
- seaborn
- matplotlib
- numpy
- statsmodels
- scikit-learn
- Prophet


