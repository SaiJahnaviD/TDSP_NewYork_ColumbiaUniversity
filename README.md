# 🚗 NYC - Motor Vehicle Collisions – End-to-End Data Science & Geospatial Analysis Project

A comprehensive transportation data science project analyzing over a decade of NYC crash data using Python, time series analysis, and geospatial visualization to generate actionable road-safety insights for vulnerable road users.

---

## 📌 Project Overview

This project is part of the **Explorer Transportation Data Science Project (TDSP)** hosted by the **Northeast Big Data Innovation Hub** and **National Student Data Corps**, in collaboration with the **U.S. Department of Transportation – Federal Highway Administration (FHWA)**.

The goal is to leverage real-world transportation data to:

* Understand crash patterns over time and space
* Identify high-risk locations and time periods
* Analyze contributing factors and vehicle involvement
* Support data-driven safety recommendations for policymakers
* Improve safety for pedestrians, cyclists, and motorists

All analysis is implemented in a single Google Colab notebook and version-controlled in this repository.

### All "TO DO" steps in google colab are provided by the colab creator and answered by me.
### Google Colab Executed Link: [NYC_Traffic_TDSP](https://colab.research.google.com/drive/15DWn3xisJco_j2x582eO1Krr-wSUvAYg?usp=sharing)
---

## 🧠 Key Research Questions

* How do crash frequency and severity vary by **time of day** and **day of week**?
* How did **COVID-19** impact traffic collisions over time?
* Which **boroughs and intersections** are most dangerous?
* What factors contribute most to crashes?
* How can data guide **transportation safety improvements** and equitable infrastructure planning?

---

## 🗂 Dataset

* **Source:** NYC Open Data – Motor Vehicle Collisions (Crashes)
* **Records:** Millions of police-reported crashes
* **Time span:** 2014 – 2024
* **Features include:**

  * Date & time of crash
  * Location (latitude, longitude, borough, streets)
  * Injuries & fatalities (pedestrians, cyclists, motorists)
  * Vehicle types
  * Contributing factors

---

## ⚙️ Tech Stack & Tools

| Category             | Tools               |
| -------------------- | ------------------- |
| Language             | Python              |
| Data Processing      | Pandas, NumPy       |
| Visualization        | Matplotlib, Seaborn |
| Geospatial Mapping   | Folium              |
| Time Series Analysis | statsmodels         |
| Environment          | Google Colab        |
| Version Control      | Git & GitHub        |

---

## 🚀 Project Milestones & Features

### 1️⃣ Data Preparation & Exploration

* Dataset loading & cleaning
* Data type conversion
* Summary statistics using `describe()`
* Missing value analysis with percentages

---

### 2️⃣ Data Ethics & Bias Assessment

* Analysis of missing geographic and demographic data
* Discussion of:

  * Under-reporting in under-resourced communities
  * Data collection limitations
  * Reporting bias
  * Ethical considerations in transportation datasets

---

### 3️⃣ Time Series Analysis

**Implemented:**

* Hour-of-day crash analysis
* Monthly crash trends
* COVID-19 impact visualization
* Daily crash time series decomposition:

  * Trend
  * Seasonality
  * Residuals

**Key insight:**

* Crashes peak around **4 PM (evening rush hour)**
* Major decline in 2020 due to lockdowns

---

### 4️⃣ Geospatial Analysis

**Visualizations created:**

* Borough-level crash distribution
* Interactive crash heatmap
* Severity-coded crash map using:

  * Shapes (circles, squares, triangles)
  * Colors
  * Accessibility-aware design

**Findings:**

* Highest crashes: Brooklyn
* Lowest crashes: Staten Island
* Major hotspots:

  * Midtown Manhattan
  * Lower Manhattan
  * Queens Boulevard corridor
  * Times Square intersection

---

### 5️⃣ Self-Guided Research & Visualization

* Designed and implemented:

  * Day-of-week × Hour-of-day crash frequency heatmap
* Focus on:

  * Rush hour risk windows
  * Weekday vs weekend patterns
  * Equity-aware safety planning

---

### 6️⃣ Data Storytelling & Policy Recommendations

Developed DOT-focused recommendations:

* Rush-hour traffic enforcement
* Pedestrian infrastructure in hotspots
* High-risk intersection redesign
* Equity-based road investment
* Improved crash data standardization

---

## 📊 Sample Visual Outputs

* Crash frequency heatmaps
* Time series trend plots
* Interactive folium maps
* Severity-coded geospatial layers

*(Open `heatmap.html` and `severity.html` locally to view interactive maps)*

---

## 🏆 Impact & Value

This project demonstrates:

- Real-world data handling at scale
- Time series modeling & decomposition
- Geospatial analysis
- Data ethics awareness
- Visualization best practices
- Policy-oriented insights
- End-to-end data science workflow

Suitable for roles in:

* Data Science
* Transportation Analytics
* Urban Analytics
* GIS Engineering
* Applied Machine Learning
* Public Policy Data Analysis

---

## 📌 Future Enhancements

* Integrate weather datasets
* Add census & income demographics
* Build crash severity prediction model
* Forecast future crash trends
* Network-based road analysis
* Automated dashboard deployment

---

## 📚 References

* NYC Open Data – Motor Vehicle Collisions Dataset
* National Student Data Corps
* Northeast Big Data Innovation Hub
* Statsmodels Documentation
* Seaborn & Matplotlib Documentation

---
