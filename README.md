# 🚇 NYC Transit Equity Analysis
*A comprehensive data-driven analysis revealing critical disparities in New York City's overnight public transportation system*

[![Python](https://img.shields.io/badge/Python-3.13-blue.svg)](https://www.python.org/)
[![SQL](https://img.shields.io/badge/SQL-DuckDB-orange.svg)](https://duckdb.org/)
[![Data](https://img.shields.io/badge/Data-13.2M%20Records-green.svg)](#)

**🌐 [Live Portfolio Website](https://ewiges3317.github.io/Final_NYC_Transit_Equity/) | 📊 [View Presentation](docs/nyc_transit_equity_presentation.pdf) | 💻 [Analysis Notebook](notebooks/nyc_taxi_analysis.ipynb)**

---

## 🎯 Executive Summary

This project analyzes **13.2 million NYC taxi trips** to uncover critical transit equity gaps affecting overnight workers and outer borough residents. Using advanced SQL processing and statistical analysis, I identified specific neighborhoods where residents depend on overnight transportation for up to **59% of their trips**, revealing systemic inequities in public transit access.

### 🔑 Key Findings

| Finding | Impact | Location |
|---------|---------|----------|
| **59% Overnight Dependency** | Lower East Side residents rely on overnight transit for majority of trips | Manhattan |
| **12.1% Equity Gap** | Staten Island residents face 12.1 percentage points higher overnight reliance than Manhattan | Borough-wide |
| **11.7x Service Drop** | Demand falls from 335K trips (10PM) to 29K trips (5AM) but transportation needs persist | Citywide |

---

## 📊 Data Visualizations

### Top 5 Zones with Highest Overnight Transit Dependence
![Top 5 Zones](visualizations/top_5_zones_overnight_reliance_simple.png)

### Geographic Transit Equity Gap Across NYC Boroughs  
![Borough Equity Gap](visualizations/borough_equity_gap_simple.png)

### Critical Service Gaps During Overnight Hours
![Service Gap Timeline](visualizations/overnight_service_gap_timeline_simple.png)

---

## 💼 Business Impact & Policy Implications

### 🎯 **Targeted Solutions Proposed**
- **Phase 1**: Increase service frequency in top 5 highest-need zones
- **Phase 2**: Address outer borough transit gaps (Staten Island, Brooklyn)  
- **Phase 3**: Optimize service scheduling for early morning essential workers

### 💰 **Expected Economic Benefits**
- **$1,200-1,800** annual savings per worker through improved transit access
- **30-50%** reduction in wait times for high-need communities
- **15%** projected increase in late-night ridership

---

## 🛠️ Technical Implementation

### **Data Pipeline Architecture**
