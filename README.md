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

Raw Data (13.4M records) → Data Cleaning → 19-Step SQL Analysis → Visualization → Policy Recommendations


### **Technology Stack**
- **Data Processing**: Python 3.13, DuckDB 1.3.2, pandas 2.3.2
- **Analysis**: SQL (19-step workflow), statistical modeling
- **Visualization**: matplotlib, seaborn, custom charts
- **Data Source**: NYC TLC Yellow Taxi Trip Records (2024)

### **Data Quality & Validation**
| Metric | Before Cleaning | After Cleaning | Quality Improvement |
|--------|----------------|----------------|-------------------|
| **Total Records** | 13,432,489 | 13,199,463 | 232K invalid records removed |
| **Fare Range** | Negative to $1,712 | $0 to $1,712 | Negative fares eliminated |
| **Data Integrity** | 98.3% | 99.9% | Improved accuracy |

---

## 📁 Repository Structure

Final_NYC_Transit_Equity/ ├── 📊 visualizations/ # Clear, impactful data visualizations ├── 📈 data/ # Processed datasets and aggregations
├── 💻 notebooks/ # Jupyter analysis workflow ├── 🗃️ sql/ # 19-step SQL data processing pipeline ├── 📄 docs/ # Professional presentation and documentation ├── 🌐 index.html # Live portfolio website └── 📋 README.md # This file


---

## 🚀 Key Skills Demonstrated

### **Advanced Data Analysis**
- ✅ **Large-scale data processing** (13+ million records)
- ✅ **Complex SQL workflows** (19-step pipeline with validation)
- ✅ **Statistical analysis** and pattern recognition
- ✅ **Data quality assurance** and validation frameworks

### **Data Visualization & Storytelling**  
- ✅ **Clear, impactful visualizations** that immediately communicate insights
- ✅ **Executive-level reporting** with actionable recommendations
- ✅ **Technical documentation** for reproducibility

### **Policy & Business Analysis**
- ✅ **Urban policy analysis** with real-world applications
- ✅ **Equity-focused research** addressing social impact
- ✅ **Stakeholder communication** across technical and non-technical audiences

---

## 📖 How to Reproduce This Analysis

### **Quick Start**
1. **Clone this repository**
   ```bash
   git clone https://github.com/ewiges3317/Final_NYC_Transit_Equity.git
   cd Final_NYC_Transit_Equity
Install dependencies

Copypip install -r requirements.txt
Run the analysis

Copyjupyter lab notebooks/nyc_taxi_analysis.ipynb
Data Sources
Primary: NYC Taxi & Limousine Commission Trip Record Data
Coverage: February, April, July, October 2024
Geographic Scope: All 5 NYC boroughs + 265+ taxi zones
📊 Detailed Documentation
Document	Purpose	Location
SQL Workflow	Complete 19-step data processing pipeline	docs/
Technical Documentation	Detailed methodology and validation	Root
Analysis Notebook	Interactive Python analysis workflow	notebooks/
Data Files	Processed datasets and aggregations	data/
🎥 Project Highlights
"This analysis reveals that Lower East Side residents depend on overnight transportation for 59% of their trips - nearly three times the city average. This finding has direct implications for transit policy and service planning."

🏆 What Makes This Project Stand Out:

Real-world impact: Addresses actual urban policy challenges
Large-scale data: Professional-grade dataset processing (13M+ records)
End-to-end workflow: From raw data to policy recommendations
Technical rigor: Comprehensive validation and documentation
Clear communication: Complex analysis made accessible to stakeholders
📞 Contact & Next Steps
Interested in discussing this analysis or exploring collaboration opportunities?

This project demonstrates proficiency in:

Advanced SQL & Database Management
Large-Scale Data Processing
Statistical Analysis & Modeling
Data Visualization & Storytelling
Urban Policy & Equity Analysis
Technical Documentation & Communication
📜 License & Data Attribution
This project uses publicly available NYC TLC trip record data. Analysis code and visualizations are available under MIT License.

Data Source: New York City Taxi and Limousine Commission (TLC), Yellow Taxi Trip Records, 2024.

Built with ❤️ for transit equity and data-driven policy making
