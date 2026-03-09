# 🌫️ Air Quality Index (AQI) Data Analysis

## Overview
A comprehensive exploratory data analysis project on a 
self-generated Air Quality Index dataset spanning multiple 
cities, seasons, and environmental conditions. This project 
investigates the key factors driving air pollution and 
uncovers meaningful patterns through statistical analysis 
and visualization.

## 🔍 Key Findings

- **PM2.5 and AQI** show a strong directly proportional 
  relationship — higher PM2.5 consistently leads to worse AQI
- **Wind speed acts as a moderator** — vehicle density causes 
  dramatically worse AQI under low wind conditions compared 
  to high wind, revealing a significant interaction effect
- **Rainfall improves AQI** — monsoon seasons show noticeably 
  better air quality as rain washes pollutants from the air
- **Coal ban impact** — periods with active coal bans show 
  AQI category predominantly in "Good", while no-ban periods 
  show predominantly "Severe" categories
- **Beijing policy analysis** — average AQI reduced 
  significantly after China's 2013 pollution control policy 
  shift, validating real-world policy effectiveness
- **Highland vs Lowland terrain** — highland areas like 
  mountains show better AQI due to lower human activity 
  density
- **Green cover** is inversely proportional to AQI — 
  higher green cover areas consistently show lower pollution

## 🛠️ Tech Stack
- Python
- pandas
- NumPy
- Matplotlib
- Seaborn

## 📊 Analysis Performed
- Data cleaning and inconsistency resolution
- Category standardisation (season names, terrain grouping)
- Univariate and bivariate analysis
- Correlation heatmap across all numerical features
- Seasonal PM2.5 trend analysis
- City-level comparative analysis (Delhi vs Beijing)
- Feature engineering — terrain categorisation, wind speed 
  binning using qcut
- Policy impact analysis (Beijing pre/post 2013)
- Interaction effect analysis (vehicle density × wind speed)

## 📁 Dataset
Self-generated dataset covering:
- Multiple cities including Delhi and Beijing
- Variables: AQI, PM2.5, PM10, NO2, wind speed, rainfall, 
  temperature, vehicle density, population, green cover, 
  terrain, season, coal ban status, year

## 💡 What Makes This Project Unique
Unlike standard Kaggle datasets, this dataset was 
self-generated — demonstrating end-to-end data collection 
strategy, domain understanding, and the ability to structure 
raw data for meaningful analysis.
