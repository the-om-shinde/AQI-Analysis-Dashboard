# AQI-Analysis-Dashboard
🧭 Project Overview
A dynamic and interactive Power BI dashboard designed to analyze air quality across India using PM2.5 as a key indicator. The dashboard provides insights into pollution distribution across cities, states, and zones to identify high-risk regions and environmental trends.

🎯 Purpose
This project aims to:
Understand air quality distribution across India
Identify highly polluted cities and regions
Provide a simplified and consistent analysis using PM2.5
Highlight gaps in monitoring infrastructure

🛠 Tech Stack
📊 Power BI Desktop – Dashboard creation and visualization
🔄 Power Query – Data cleaning and transformation
📁 Excel Dataset (Kaggle - CPCB India) – Data source
🔗 Data Modeling – Relationships between city, state, station, and zone
📂 Data Source
Source: Kaggle (CPCB India AQI Dataset)
Data includes:
Cities
States & Union Territories
Monitoring Stations
Pollutant Levels (PM2.5, PM10, NO2, CO, SO2, Ozone, NH3)

⚙️ Key Design Decision
Instead of averaging all pollutants, PM2.5 is used as the primary indicator because:
It has the most severe health impact
Different pollutants have different scale thresholds
Using one consistent metric avoids misleading comparisons

📈 Features / Highlights
🔹 Business Problem
Air pollution is a major concern in India, but understanding its distribution across regions and pollutants is complex due to varying measurement scales and incomplete data.
🔹 Dashboard Goals
Provide a simplified view of AQI using PM2.5
Enable filtering by Zone → State → City → Station
Identify pollution hotspots
Analyze pollutant-wise distribution separately

🔹Key Visuals
Overview Page
KPI Cards (Cities, Stations, Avg PM2.5, States/UTs)
AQI Category Distribution (Donut Chart)
Top 10 Most Polluted Cities
State Analysis Page
Zone-wise filtering
Top polluted states
City-level AQI map
Monitoring station distribution
Pollutant Analysis Page
Tree Map of pollutant averages
Multi-bar chart comparing pollutants across states

🔹 Key Insights
Air quality across India is largely concentrated in Poor to Severe categories
Northern cities (especially Delhi) consistently show highest PM2.5 levels
Pollution is regionally concentrated, not evenly distributed
Some states and UTs show missing or limited data, indicating gaps in monitoring infrastructure

📊 Business Impact
Helps identify high-risk pollution zones
Useful for policy planning and environmental monitoring
Supports data-driven decision making
Highlights need for improved monitoring systems in certain regions

⚠️ Limitations
Some states/UTs have missing or incomplete data
Results may vary due to unequal number of monitoring stations
