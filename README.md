ETL Pipeline Weather Data Analysis

## Project Overview
Built a complete ETL (Extract, Transform, Load) pipeline that extracts real-time weather data from OpenWeather API for Nigerian cities, transforms it with Pandas, and analyzes patterns.

## Dataset
 Source: OpenWeather API (Free tier)
 Cities: Lagos, Ibadan, Akure, Abuja, Port Harcourt
 Fields: 20 (temperature, humidity, wind speed, rainfall, etc.)
 Records: 5

## Key Findings
  Hottest:** Akure (29.33°C)
  Highest Humidity: Lagos (84%)
  Strongest Wind: Lagos (4.11 m/s)
  Rainfall: 3 cities experiencing rain
  Weather: 60% rainy, 40% cloudy

## Technologies Used
 Python 3.13
 Pandas (data transformation)
 Requests (API calls)
 Matplotlib (visualization)
 Jupyter Colab

## Files
 `Week7_ETL_Pipeline.ipynb` - Main notebook with all code
 `weather_data.csv` - Processed weather data
 `README.md` - This file

## How to Run
1. Open `Week7_ETL_Pipeline.ipynb` in Google Colab
2. Run cells 1-9 (extraction, transformation, analysis)
3. Run chart cells (21-34) for visualizations
4. Check `weather_data.csv` for processed data

## ETL Process
1. **Extract:** Pull weather data from OpenWeather API
2. **Transform:** Clean, rename columns, convert timestamps, create derived fields
3. **Load:** Save to CSV for analysis
4. **Analyze:** Generate insights and visualizations

## Author
Fajorin Richard Obanijesu

## Program
AnalystLab Africa Data Analytics Internship (Week 7/8)

## Status
Complete - Ready for submission
