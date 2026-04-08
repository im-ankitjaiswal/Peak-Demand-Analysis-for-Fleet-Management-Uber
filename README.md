# 🚖 Uber NYC Fleet Management — Peak Demand Analysis

## 📌 Project Overview

This project analyzes Uber ride data (~200K records) to uncover **temporal and spatial demand patterns**, enabling **data-driven fleet optimization**, **pricing strategies**, and **operational efficiency improvements**.

It combines:

* **Exploratory Data Analysis (EDA)**
* **Geospatial Analysis**
* **Power BI Dashboarding**
* **Business Decision Modeling**

---

## 🎯 Problem Statement

Ride-hailing platforms face:

* Demand spikes at specific hours and locations
* Inefficient fleet allocation
* Missed revenue opportunities

This project identifies **when and where demand peaks** to improve:

* Driver allocation
* Revenue generation
* Customer experience

---

## 🔥 Key Features (What Makes This Project Stand Out)

### ⏱️ Datetime Feature Engineering

* Extracted:

  * Hour
  * Day of week
  * Month
* Enabled **time-based demand analysis**

---

### 🌍 Haversine Distance Calculation

* Converted GPS coordinates into **real-world trip distance (km)**
* Used for:

  * Distance analysis
  * Fare validation

---

### 🗺️ Geospatial Analysis (Folium)

* Built **interactive NYC pickup heatmap**
* Identified:

  * High-demand zones
  * Ride clustering patterns

---

### 📊 Advanced Visualizations

* Hour × Day heatmap (peak demand detection)
* Dual-axis chart (ride count + avg fare)
* Power BI dashboard with KPIs

---

### ⚙️ Power BI Data Modeling (Advanced)

* Implemented **custom categorical sorting**:

  * `day_of_week → Day_Order`
  * `time_period → period_num`

* Resolved **circular dependency issue**:

  * Avoided column inter-dependency
  * Used base columns (hour) for safe calculations

👉 Demonstrates strong understanding of **data modeling & BI tools**

---

## 📊 Dataset

* ~200,000 Uber rides
* Features:

  * Pickup & dropoff coordinates
  * Fare amount
  * Passenger count
  * Timestamp

---

## ⚙️ Tech Stack

* **Python**: Pandas, NumPy
* **Visualization**: Matplotlib, Seaborn
* **Geospatial**: Folium
* **BI Tool**: Power BI

---

## 📸 Key Visualizations

### 🔥 1. Hour × Day Heatmap

![Heatmap](images/heatmap.png)

👉 Highlights **peak demand windows**
👉 Used for fleet deployment planning

---

### 🌍 2. NYC Pickup Heatmap

![Geo Heatmap](images/geo_heatmap.png)

👉 Shows **high-demand geographic clusters**

---

### 📊 3. Power BI Dashboard

![Dashboard](images/dashboard.png)

---

## 📈 Key Insights

### ⏰ Time-Based Demand

* Peak: **Evening (6–9 PM)**
* Secondary peak: Morning commute
* Lowest: Early morning (4–6 AM)

---

### 📅 Weekly Trends

* Highest revenue: **Thursday & Friday**
* Lowest: Monday

---

### 💰 Revenue Metrics

* Total Revenue: **2.17M**
* Total Rides: **192K**
* Avg Fare: **11.32**

---

### 🚗 Demand Behavior

* Evening rush drives maximum rides
* Off-peak still contributes significantly
* Opportunity to optimize morning demand

---

## 🧠 Business Recommendations

### 🚀 Fleet Allocation

* Increase drivers during:

  * Evening peak
  * End-of-week surge

---

### 💸 Pricing Strategy

* Apply surge pricing:

  * Peak hours
  * High-demand days

---

### 📍 Location Optimization

* Deploy drivers in:

  * High-density pickup zones

---

### 📉 Off-Peak Strategy

* Introduce discounts
* Improve utilization

---

## ⚠️ Challenges & Solutions

### ❌ Circular Dependency Issue

* Faced error while sorting categorical variables in Power BI
* Cause:

  * Interdependent calculated columns

### ✅ Solution:

* Rebuilt logic using **base columns (hour)**
* Ensured **one-way dependency**

---

### ❌ Incorrect Sorting of Categories

* Days and time periods sorted alphabetically

### ✅ Solution:

* Created:

  * `Day_Order`
  * `period_num`
* Applied **Sort by Column**


## ⭐ Conclusion

This project demonstrates how combining:

* Data analysis
* Geospatial intelligence
* Business thinking

can solve real-world problems in ride-hailing platforms.

---
