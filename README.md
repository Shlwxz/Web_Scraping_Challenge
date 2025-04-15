# 🚀 Mars Data Scraping & Climate Insights

This project uses web scraping techniques to gather and explore information about Mars, including recent news articles and climate patterns recorded by NASA's Curiosity rover.

## 🛰️ Project Overview

This challenge is split into two key tasks:

### 🔴 Part 1: Mars News Headlines
- Automates browsing with Splinter
- Parses HTML using BeautifulSoup
- Scrapes article titles and previews from the Mars News site
- Stores results in a list of dictionaries
- (Optional) Saves data as a `.json` file for reuse

### 🟠 Part 2: Mars Weather Data
- Scrapes a temperature data table from a webpage
- Parses the HTML into a Pandas DataFrame
- Converts columns to correct data types
- Analyzes trends in:
  - Temperature
  - Atmospheric pressure
  - Earth vs Martian calendar time
- Exports the cleaned DataFrame to CSV
- Includes bar charts for seasonal variations

## 🔧 Technologies
- Python
- BeautifulSoup
- Splinter (for automated browsing)
- Pandas
- Matplotlib

## 📊 Data Output Examples

- `mars_weather_data.csv` — A cleaned dataset with weather stats
- `part_1_mars_news.ipynb` — Notebook scraping article titles + previews
- `part_2_mars_weather.ipynb` — Analysis & visualization of Martian weather patterns

## 📈 Visualizations

- Bar chart: Avg. monthly min temperatures on Mars
- Bar chart: Avg. monthly atmospheric pressure
- Line plot: Daily min temps across Martian year (to estimate Earth days in Martian year)
