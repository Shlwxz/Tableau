# Tableau
# 🚲 NYC Citi Bike Data Analysis (Tableau Story)

## 📍 Project Overview

This analysis explores bike-sharing trends across New York City using data from the Citi Bike program. Using Tableau, we identified two key phenomena supported by 8 visualizations, 2 dashboards, and an interactive map.

## 📊 Dashboards

### 1. Weekday vs Weekend Ridership
- **Visualizations:**
  - Total Trips by Hour
  - Breakdown by User Type
  - Day of Week Heatmap
- **Key Insight:** Weekday ridership spikes around commute hours, while weekend usage is more evenly spread.

### 2. Station Popularity by Zip Code
- **Visualizations:**
  - Top 10 Start/End Stations
  - Monthly Trends (Dropdown filter)
  - Interactive Map with Zip Overlay
- **Key Insight:** Midtown and Financial District stations dominate weekday traffic; parks and riverside stations rise in summer weekends.

## 🗺️ Map Highlights

- Stations sized by number of trips
- Colors indicate trip volume buckets
- Zip codes overlaid for regional context
- Trend: Central business districts consistently drive high activity

## 📈 Notable Phenomena

1. **Seasonal Peaks in Casual Users**
   - Casual rider volume increases significantly from May to September.
   - Avg. trip duration is longer for casual users, especially in summer.

2. **Member Commuting Behavior**
   - Annual members show consistent 8–9AM and 5–6PM usage.
   - These patterns align closely with weekday working hours.

## 🔍 Data Notes

- Time Period: [e.g. June–August 2023]
- Cleaned for missing/erroneous birth years and start/end times
- Converted trip duration from seconds to minutes
- Created calculated fields for hour, day, and month
