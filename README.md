# AQI Analysis Dashboard

## Project Overview

A dynamic and interactive Power BI dashboard designed to analyze air quality across India. The dashboard provides insights into air quality distribution across cities, states, and zones, while also analyzing pollutants to identify high-risk regions and environmental trends.

The project uses PM2.5 as the primary indicator for consistent air-quality comparisons and separately analyzes multiple pollutants, including PM10, PM2.5, CO, NO2, Ozone, SO2, and NH3.

## Tools & Technologies Used

- Power BI Desktop
- Power Query
- Excel Dataset (Kaggle - CPCB India)
- Data Modeling
- GitHub

## Dataset Information

**Source:** Kaggle (CPCB India AQI Dataset)

### Data Includes

- Cities
- States & Union Territories
- Monitoring Stations
- Pollutants (PM2.5, PM10, NO2, CO, SO2, Ozone, NH3)

## Key Features

### Key Design Decision

PM2.5 is used as the primary indicator for consistent air-quality comparisons because:

- It has the most severe health impact
- Different pollutants have different scale thresholds
- Using one consistent metric avoids misleading comparisons

Other pollutants are analyzed separately to understand their distribution and levels across states and Union Territories.

### Business Problem

Air pollution is a major concern in India, but understanding its distribution across regions and pollutants is complex due to varying measurement scales and incomplete data.

### Dashboard Goals

- Provide a simplified view of air quality using PM2.5
- Enable filtering by Zone → State → City → Station
- Identify pollution hotspots
- Analyze pollutant-wise distribution separately
- Compare pollutant levels across states and Union Territories

## Dashboard Pages

### Overview Page

- KPI Cards (Cities, Stations, Avg PM2.5, States/UTs)
- Air Quality Category Distribution
- Top 10 Most Polluted Cities
- City selection filter
- Key insights based on air-quality distribution and PM2.5 levels

### State Analysis Page

- City-wise AQI analysis
- Top 10 Polluted States & Union Territories
- Zone → State → City → Station filtering
- City-level AQI map
- Monitoring station analysis
- Key insights based on regional pollution patterns

### Pollutant Analysis Page

- Average pollutant analysis using a Tree Map
- Analysis of PM10, PM2.5, CO, NO2, Ozone, SO2, and NH3
- Pollutant filtering by city and station
- Pollutant distribution across states and Union Territories
- Multi-bar chart comparing pollutant levels across states

## Key Insights

- Air quality across India is largely concentrated in Poor to Severe categories
- Northern cities, especially Delhi, consistently show high PM2.5 levels
- Pollution is regionally concentrated, not evenly distributed
- PM10 has the highest average among the analyzed pollutants, while PM2.5 is used as the primary indicator for air-quality comparisons
- Delhi and Uttar Pradesh show high levels across multiple pollutants
- Some states and Union Territories show missing or limited data, indicating gaps in monitoring infrastructure

## Business Impact

- Helps identify high-risk pollution zones
- Useful for policy planning and environmental monitoring
- Supports data-driven decision making
- Enables comparison of pollutant levels across regions
- Highlights the need for improved monitoring systems in certain regions

## Limitations

- Some states and Union Territories have missing or incomplete data
- Results may vary due to unequal number of monitoring stations
