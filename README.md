# Tableau
# 🚲 NYC Citi Bike Data Analysis (Tableau Story)

## 📍 Project Overview

This analysis explores bike-sharing trends across New York City using data from the Citi Bike program. Using Tableau, we identified two key phenomena supported by 8 visualizations, 2 dashboards, and an interactive map.

## 📊 Dashboards

# 📊 NYC Citi Bike Analysis – Tableau Story
**Project:** Module 18 – Citi Bike Tableau Challenge  
**Link to Dashboard:**  
🔗 [View on Tableau Public](https://public.tableau.com/app/profile/shahla.shahnawaz/viz/Book2_17447122414290/Story1)

---

## 🚴 Overview

This interactive Tableau Story explores usage trends in New York City’s Citi Bike program using data from **2020** and **2023**. The goal is to identify **unexpected phenomena** in rider behavior to help city officials make informed decisions about infrastructure, bike availability, and policy planning.

---

## 📌 Key Questions Answered

1. **When and how do members vs. casual riders use Citi Bikes?**
2. **How does ride duration vary by user type and day?**
3. **Which stations are most popular, and where might attention be needed?**

---

## 🧭 What’s Inside the Story

### 📍 Slide 1: Weekend Riding Patterns
- Shows that **casual users** ride longer on **weekends**
- Visuals include average trip duration by rider type and day
- Implication: Weekend bike availability and scenic routes matter more for casual users

### 📍 Slide 2: Weekday Commute Trends
- Highlights that **members ride most during commute hours**
- Clear spikes at 8 AM and 5–6 PM, Monday–Friday
- Suggests the importance of maintaining bike availability at **transit hubs**

### 📍 Slide 3: Station Heatmap
- Interactive map showing popular start stations
- Marker size = ride volume, color = average trip duration
- Key finding: **Midtown, Downtown, and Parks** dominate usage

### 📍 Slide 4: Summary
- Recaps key takeaways:
  - Casual users = long weekend rides
  - Members = weekday commute focus
  - Central NYC sees highest traffic

---

## 📈 Datasets Used
- Combined Citi Bike trip data for 2020 & 2023 (cleaned/enriched)
- Added fields:
  - `trip_duration_minutes`
  - `start_hour`, `day_of_week`, `month`
  - `member_casual`, `weekday_vs_weekend`

---

## ✅ For City Officials

This dashboard allows NYC policymakers to:
- Adjust bike rebalancing by **day and rider type**
- Optimize station design at **commuter hubs**
- Plan for **tourism-heavy weekend areas**
- Identify underserved neighborhoods

---

## 🧰 Tools Used
- Tableau Public
- Data Cleaning in Python (Pandas)
- D3 Geospatial Logic (Map layers)

