# Climate Change Explorer: Temperatures & Precipitation

## Description
This project investigates long-term climate change patterns by analyzing global and regional **temperature anomalies** and **precipitation trends**. Using publicly available climate datasets, the project explores how climate indicators have changed over time and visualizes key trends with Python.

**The goal is to:**

- Understand long-term warming trends
- Examine changes in seasonal precipitation
- Compare regional vs. global climate patterns
- Practice data wrangling, visualization, and time-series analysis in Python

## Author
Yuan Ying  

## Date
05/02/2025  

---

## How It's Made:

**Tech used:** R, Shiny, tidyverse, leaflet, plotly, sf

This project was built as an interactive Shiny web application using R. I used **tidyverse** for data wrangling and visualization, **sf** and **maps** packages to handle California county polygons for choropleth mapping, **leaflet** for interactive web maps, and **plotly** for dynamic exploratory plots.  

The crash data (2021–2023) was cleaned and preprocessed in R to allow filtering by year, location, county, and violation category. Interactive features include clickable crash points, choropleth maps showing county-level crash counts, and faceted trend plots by collision type and severity.  

This project showcases my ability to combine data cleaning, geospatial mapping, and interactive visualization to make complex datasets accessible and insightful.

## Packages
The project is implemented in Python, using:

`pandas` — data cleaning and wrangling

`numpy` — numeric computation

`matplotlib` — time-series and trend plotting

`seaborn` — enhanced statistical visualizations

## Key Analyses
**1. Temperature Trend Analysis**

Load global and regional temperature anomaly data

Convert date columns to datetime format

Compute rolling averages (e.g., 5-year or 10-year)

Visualize long-term warming

Fit a linear regression to estimate warming rate (°C per decade)

  **Common plots include:**
  
  - Line plot of annual temperature anomalies
  - Rolling average smoothing
  - Trend line overlay
  - Regional vs. global comparison

**2. Precipitation Trend Analysis**

Load monthly or annual precipitation data

Aggregate by year or season

Detect long-term changes in total precipitation

  **Typical visualizations:**
  - Annual precipitation totals、
  - Seasonal precipitation patterns
  - Boxplots of distribution changes
  - Moving averages or trendlines



**3. Correlation Between Temperature & Precipitation**

Scatterplots or heatmaps

Correlation coefficients or regression models

## Lessons Learned:
In this project, I focused on creating visualizations to explore long-term temperature and precipitation patterns. By generating line charts, seasonal plots, and rolling averages, I learned how different plotting techniques can highlight climate trends that are not obvious from raw data alone. This process also improved my ability to choose appropriate visuals, interpret patterns, and communicate insights effectively through graphics. Overall, the project strengthened my data visualization skills and deepened my understanding of how climate change signals appear in real datasets.


## Data Sources:

The analysis uses standard climate datasets such as:

- Global Temperature Anomalies — e.g., NASA GISS or NOAA datasets
- Monthly or Annual Precipitation Data — e.g., NOAA Global Historical Climatology Network
- Regional Datasets (if applicable) — e.g., Berkeley Earth regional climate summaries
