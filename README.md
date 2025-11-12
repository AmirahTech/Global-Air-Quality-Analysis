# Environmental Data Analytics: Global Air Quality Trends & Forecasting

## Project Summary

This project analyzes global air quality, identifying top polluted countries and cities, examining pollutant relationships, and visualizing trends over time. It also provides a forecast of PM2.5 levels, helping highlight pollution hotspots and potential future risks. Overall, it demonstrates how data analysis and visualization can reveal actionable insights into environmental health worldwide.

**Key Goals:**
- Analyze global PM2.5 trends over time
- Identify top polluted countries and cities
- Explore correlations between pollutants
- Visualize air quality on a world map
- Forecast future PM2.5 levels

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
- Loaded the CSV dataset using `pandas`.
- Converted `Date` column to datetime.
- Checked for missing values and filled forward (though none were missing).

### 2. Global PM2.5 Trends
- Calculated daily **average PM2.5** worldwide.
- Visualized trends using line plots.

### 3. Top Polluted Countries & Cities
- Calculated average PM2.5 per country and city.
- Visualized top 20 countries and cities using bar charts.

### 4. Correlation Analysis
- Computed correlations between PM2.5, PM10, NO2, SO2, CO, O3.
- Visualized relationships using a heatmap.

### 5. Global Air Quality Map
- Created an interactive choropleth map with **Plotly** to show average PM2.5 per country.

### 6. Forecasting PM2.5 (Optional)
- Used **Prophet** to forecast global PM2.5 trends for the next 30 days.

---

## Visualizations
- Line plots for global trends.
- Bar charts for top countries and cities.
- Heatmap for pollutant correlations.
- Interactive world map for PM2.5 levels.
- Forecast plots for PM2.5 trends.

---
## Key Insights

- PM2.5 and PM10 are strongly correlated, indicating particulate matter pollution often occurs together.

- Top polluted countries include [UAE, Australia, India, Japan], showing regional hotspots.

- Top polluted cities include [Dubai, Sydney, Mumbai, Tokyo], highlighting urban pollution challenges.

- Global trends show fluctuations in air quality over time, suggesting seasonal or event-driven changes.

- Forecasting PM2.5 provides near-future estimates, useful for planning interventions and policy decisions.

