# 🚗 Motor Vehicle Collisions/Crashes Analysis 🚦

### 📄 Project Overview
This project analyzes motor vehicle collision data from **New York**, **Chicago**, and **Austin**, leveraging data warehousing techniques. Developed as part of the **DAMG 7370: Designing Advanced Data Architectures for Business Intelligence** course at **Northeastern University**, the project aims to derive meaningful insights through a structured pipeline and visualization tools.

---

### 🎯 Objectives
- 🚩 Identify accident-prone areas in the cities.
- 👣 Examine patterns involving pedestrian involvement.
- ⏰ Analyze temporal trends (e.g., peak hours, seasonal variations).
- 🔍 Explore factors contributing to collisions and fatalities.

---

### 📂 Data Sources
Data was sourced from publicly available repositories provided by city transportation departments:
1. [New York City Motor Vehicle Collisions](https://data.cityofnewyork.us/)
2. [Austin Crash Report Data](https://data.austintexas.gov/)
3. [Chicago Traffic Crashes](https://data.cityofchicago.org/)

These datasets contain detailed records of accident locations, timestamps, and severity levels.

---

### 🛠️ Key Phases

#### 1️⃣ Data Profiling and Preparation
- **Data Profiling**: Tools like **Alteryx** and **ydata profiler** were used to assess data quality.
- **Data Staging**: Raw data was cleaned and loaded into staging tables using **Talend ETL jobs**.
- **Dimensional Modeling**: Fact and dimension tables were created with clear **source-to-target mappings**.
![image](https://github.com/user-attachments/assets/e6b6b445-7e8a-4767-aaff-4946c56a7dcd)

#### 2️⃣ Integration and Transformation
- **ETL Workflow**: Staging data was processed into the integrated layer using **Talend pipelines**.
- **Data Validation**: SQL queries ensured data accuracy, identifying and addressing rejected rows.
- **Advanced Modeling**: Incorporated **Slowly Changing Dimensions (SCDs)** and **Factless Facts** to meet advanced business needs.
![image](https://github.com/user-attachments/assets/45852aa6-bbb5-4c47-9792-053ff6d2974e)

#### 3️⃣ Visualizations and Insights
- **Visualization Tools**: **Tableau** and **Power BI** dashboards provided interactive insights.
- **Focus Areas**: Temporal trends, injury reports, and accident hotspots.
- **Deliverables**: Screenshots and source files of visualizations are included.

---

### 🔍 Insights and Findings
This project tackled the following key business questions:
- 📊 **Accident Statistics**: What’s the total number of accidents in each city?
- 📍 **Hotspot Locations**: Where are the top 3 accident-prone areas?
- 🛑 **Injury Reports**: How many accidents led to injuries or fatalities?
- 🚶 **Pedestrian Involvement**: How often were pedestrians involved in accidents?
- ⏱️ **Temporal Trends**: What are the peak times, days, and seasons for accidents?
- ☠️ **Fatalities**: Which areas have the most fatal accidents?
- ⚠️ **Common Causes**: What factors frequently contribute to accidents?

---

### 📊 Deliverables
This repository contains:
1. **Staging and Integration Artifacts**: ETL workflows, dimensional models, and transformation mappings.
2. **SQL Scripts**: Queries used for validation and business question analysis.
3. **Visual Dashboards**: Comprehensive insights presented using Tableau and Power BI.

---

