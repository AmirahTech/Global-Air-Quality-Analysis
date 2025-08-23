# Global-Air-Quality-Analysis


## Project Overview
This project analyzes **global air quality data** to explore trends, identify polluted regions, and study relationships between different pollutants. Using a dataset of cities worldwide, it visualizes global pollution patterns and optionally forecasts future air quality trends.

**Key Goals:**
- Analyze global PM2.5 trends over time
- Identify top polluted countries and cities
- Explore correlations between pollutants
- Visualize air quality on a world map
- Forecast future PM2.5 levels (optional)

---

## Dataset
The dataset is sourced from Kaggle: [Global Air Quality Dataset](https://www.kaggle.com/datasets/waqi786/global-air-quality-dataset)

**Columns include:**
- `City`, `Country`, `Date`
- Pollutants: `PM2.5`, `PM10`, `NO2`, `SO2`, `CO`, `O3`
- Weather info: `Temperature`, `Humidity`, `Wind Speed`

---

## Project Steps

### 1. Data Loading & Cleaning
- Loaded the CSV dataset using `pandas`
- Converted `Date` column to datetime
- Checked for missing values (none in this dataset)

### 2. Global PM2.5 Trends
- Calculated daily and monthly **average PM2.5** worldwide
- Visualized using line plots to observe trends over time

### 3. Top Polluted Countries & Cities
- Calculated average PM2.5 per country and city
- Visualized top 20 countries and top 20 cities using bar charts

### 4. Correlation Analysis
- Computed correlations between pollutants (PM2.5, PM10, NO2, SO2, CO, O3)
- Plotted a **heatmap** to see how pollutants relate to each other

### 5. Global Air Quality Map
- Used **Plotly choropleth map** to visualize average PM2.5 per country
- Redder countries indicate higher pollution levels

### 6. Forecasting PM2.5 (Optional)
- Used **Prophet** for time series forecasting
- Predicted global PM2.5 levels for the next 30 days

---

## Visualizations
- Line plots for global trends
- Bar charts for top countries and cities
- Heatmap for pollutant correlations
- Interactive world map for PM2.5 levels
- Forecast plots for PM2.5 trends


