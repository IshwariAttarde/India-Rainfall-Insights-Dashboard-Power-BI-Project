# India-Rainfall-Insights-Dashboard-Power-BI-Project
This project explores rainfall patterns across Indian states and districts using Power BI. The dashboard provides interactive insights into rainfall distribution, seasonal trends, and anomalies to support decision-making in areas like agriculture, water management, and climate research.
# 🌧️ RainScape: India Rainfall Dashboard (Power BI)

## 📌 Project Overview  
The **RainScape Dashboard** is a Power BI project that visualizes **district-wise and state-wise rainfall in India**.  
It enables users to explore **seasonal patterns, anomalies, and regional rainfall distribution** for better insights in agriculture, water management, and climate research.  

---

## 🔑 Key Features  
- 📊 **KPIs & Metrics**  
  - Total Annual Rainfall  
  - Average Rainfall per District  
  - State & District with Highest Rainfall  
  - Best & Worst Seasons (name + value)  
- 🌍 **Geospatial Analysis**  
  - Drilldown Map (State → District)  
  - Shape/Filled Map with rainfall saturation  
- 📅 **Temporal Trends**  
  - Monthly Rainfall Line Chart (Jan–Dec)  
  - Seasonal Rainfall (Jan-Feb, Mar-May, Jun-Sep, Oct-Dec)  
- 🚦 **Advanced Indicators**  
  - Deviation vs National Average (arrows, colors, values)  
  - Rainfall Anomaly Index (z-score)  
  - Top 10 States & Districts by Rainfall  

---

## 🛠️ Tech Stack  
- **Tool**: Microsoft Power BI (2025 update)  
- **Data Source**: District-wise Rainfall (CSV dataset)  
- **Data Model**:  
  - Fact tables → `Rainfall`, `Monthly`, `Seasonal`  
  - Dimension table → `DimState`  
- **DAX Measures**:  
  - Custom KPIs for rainfall deviation, anomaly detection, seasonal best/worst, and ranking  

---

## 📷 Dashboard Preview  
*(Insert screenshots or GIFs here)*  

Example visuals included:  
- **KPI Cards** (Annual Rainfall, Avg Rainfall, Deviation)  
- **Map Drilldown** (State → District rainfall)  
- **Line Chart** (Monthly rainfall trend)  
- **Bar Charts** (Top 10 States & Districts)  

---

## 📂 Repository Structure  
