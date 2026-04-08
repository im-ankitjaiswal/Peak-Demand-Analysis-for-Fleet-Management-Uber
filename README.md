# 🚖 Uber NYC Fleet Management — Peak Demand Analysis

## 📌 Project Overview

This project analyzes Uber ride data to identify **when and where demand peaks**, enabling smarter **fleet allocation**, **pricing strategies**, and **operational efficiency**.

Unlike typical EDA projects, this work integrates:

* **Geospatial analysis**
* **Advanced feature engineering**
* **Interactive visualization (Power BI + Folium)**

---

## 🔥 What Makes This Project Stand Out

This project goes beyond basic analysis and demonstrates **industry-relevant skills**:

### ✅ Datetime Feature Engineering

* Extracted:

  * Hour
  * Day of week
  * Month
* Enabled deep **temporal demand analysis**

👉 Core skill tested in almost every Data Analyst interview

---

### 🌍 Haversine Distance Calculation

* Converted GPS coordinates into **real-world distance (km)**
* Enabled:

  * Trip distance analysis
  * Fare vs distance validation

👉 Demonstrates ability to work with **geospatial math**

---

### 🗺️ Folium Interactive Heatmap

* Built an **interactive NYC pickup heatmap**
* Visualizes real demand clusters

👉 Highly impactful for:

* GitHub portfolio
* LinkedIn visibility

---

### 📊 Dual-Axis Visualization

* Combined:

  * Ride count (bars)
  * Average fare (line)

👉 Shows ability to present **multi-metric insights clearly**

---

## 🎯 Problem Statement

Ride-hailing platforms struggle with:

* Demand spikes at specific hours
* Poor fleet distribution
* Revenue inefficiencies

This project identifies **peak demand windows & hotspots** to optimize operations.

---

## 📊 Dataset

* ~200K+ Uber rides
* Features:

  * Pickup & dropoff coordinates
  * Timestamp
  * Fare amount
  * Passenger count

---

## ⚙️ Tech Stack

* Python (Pandas, NumPy)
* Matplotlib, Seaborn
* Folium (Geospatial Visualization)
* Power BI (Dashboarding)

---

## 🔍 Exploratory Data Analysis

### Key Steps:

* Cleaned invalid data:

  * Negative fares
  * Zero passengers
* Created time-based features
* Derived trip distance using Haversine formula
* Analyzed:

  * Hourly demand
  * Weekly patterns
  * Revenue trends

---

## 📸 Key Visualizations

### 🔥 1. Hour × Day Heatmap (Fleet Deployment Insight)

![Heatmap](images/heatmap.png)

👉 Dark regions indicate **high-demand windows**
👉 Critical for **driver allocation strategy**

---

### 🌍 2. NYC Pickup Heatmap (Folium)

![Geo Heatmap](images/geo_heatmap.png)

👉 Highlights **high-demand zones (Manhattan hotspots)**
👉 Supports **location-based fleet optimization**

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
* Lowest activity: Monday

---

### 💰 Revenue Metrics

* Total Revenue: **2.17M**
* Total Rides: **192K**
* Avg Fare: **11.32**

---

### 🚗 Demand Behavior

* Evening rush dominates ride volume
* Off-peak still contributes significantly
* Opportunity to optimize morning demand

---

## 🧠 Business Recommendations

### 🚀 Fleet Optimization

* Increase drivers during:

  * Evening peak
  * Weekends / end-of-week

---

### 💸 Smart Pricing

* Apply surge pricing:

  * High-demand hours
  * Thu–Fri peak windows

---

### 📍 Location Strategy

* Focus drivers in:

  * Manhattan hotspots
* Reduce idle time

---

### 📉 Off-Peak Optimization

* Introduce discounts
* Improve ride frequency

---

## ⚠️ Performance Note

* Haversine distance computation on ~190K rows takes **1–2 minutes**
* Avoid restarting kernel during execution

---

## 💼 Resume Highlights

* Performed **geospatial analysis using Haversine formula**
* Built **interactive heatmaps (Folium)** for demand visualization
* Engineered **time-based features** for trend analysis
* Designed **Power BI dashboard** for business insights
* Delivered **data-driven fleet optimization strategies**

---

## 📂 Project Structure

```bash
├── data/
├── notebooks/
├── images/
│   ├── heatmap.png
│   ├── geo_heatmap.png
│   └── dashboard.png
├── README.md
```

---

## ⭐ Conclusion

This project demonstrates how combining:

* Data analysis
* Geospatial intelligence
* Visualization

can drive **real-world operational decisions** in ride-hailing platforms.

---
