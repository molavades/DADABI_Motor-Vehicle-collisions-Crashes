# Motor Vehicle Collisions/Crashes Analysis

## Overview
This repository contains a comprehensive analysis of motor vehicle collision data from three major U.S. cities: **New York**, **Chicago**, and **Austin**. The project was developed as part of the **DAMG 7370: Designing Advanced Data Architectures for Business Intelligence** course at Northeastern University. The goal is to extract actionable insights from collision data, answer key business questions, and create interactive visualizations.

---

## Objectives
The primary objectives of this project include:
- Identifying accident-prone areas across cities.
- Analyzing patterns involving pedestrian involvement.
- Understanding temporal trends such as peak hours or seasonal variations.
- Exploring contributing factors to accidents and fatalities.

---

## Data Sources
Publicly available datasets from city transportation departments were utilized:
- [New York City Motor Vehicle Collisions](https://data.cityofnewyork.us/)
- [Austin Crash Report Data](https://data.austintexas.gov/)
- [Chicago Traffic Crashes](https://data.cityofchicago.org/)

These datasets provide critical details about the location, time, severity, and nature of motor vehicle collisions.

---

## Key Phases of the Project

### Phase 1: Data Profiling and Preparation
- **Data Profiling**: Tools such as **Alteryx** and **ydata profiler** were employed to assess data structure, completeness, and consistency.
- **Data Staging**: Raw data was transformed into staging tables using **Talend ETL jobs**, ensuring a clean and structured format.
- **Dimensional Modeling**: Fact and dimension tables were designed with clear **source-to-target mappings** for seamless integration.
![image](https://github.com/user-attachments/assets/3cc24ac0-dba9-4235-8f0e-380cfa8da7c3)

### Phase 2: Integration and Transformation
- **ETL Workflow**: **Talend pipelines** were created to process staging data into the integrated layer.
- **Validation**: SQL queries ensured the accuracy of transformations and provided explanations for rejected records.
- **Advanced Modeling**: The inclusion of **Slowly Changing Dimensions (SCDs)** and **Factless Facts** supported additional business requirements.
![image](https://github.com/user-attachments/assets/45852aa6-bbb5-4c47-9792-053ff6d2974e)

### Phase 3: Visualizations and Insights
- **Visualization Tools**: Leveraged **Tableau** and **Power BI** to create interactive dashboards.
- **Focus Areas**: Temporal analysis, injury statistics, and fatality trends.
- **Artifacts**: Screenshots and source files of dashboards are included for reference.

---

## Insights and Findings
This project addressed key business questions through detailed analysis:
1. **Accident Statistics**: How many accidents occurred in each city?
2. **Hotspot Areas**: Which 3 locations have the highest accident counts?
3. **Injury Reports**: How many accidents led to injuries?
4. **Pedestrian Involvement**: How often were pedestrians affected?
5. **Time Analysis**: What are the peak times, days, and seasons for accidents?
6. **Fatalities**: Which areas reported the most fatal accidents?
7. **Common Factors**: What are the shared contributing factors to collisions?

---

## Reports and Visuals
The following deliverables are included in this repository:
- **Staging and Integration Artifacts**: ETL jobs, dimensional models, and transformation mappings.
- **SQL Queries**: Scripts for answering business questions and performing data validation.
- **Dashboards**: Time-based, fatality-focused, and factor-driven visualizations.

---

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

#### 2️⃣ Integration and Transformation
- **ETL Workflow**: Staging data was processed into the integrated layer using **Talend pipelines**.
- **Data Validation**: SQL queries ensured data accuracy, identifying and addressing rejected rows.
- **Advanced Modeling**: Incorporated **Slowly Changing Dimensions (SCDs)** and **Factless Facts** to meet advanced business needs.

#### 3️⃣ Visualizations and Insights
- **Visualization Tools**: **Tableau** and **Power BI** dashboards provided interactive insights.
- **Focus Areas**: Temporal trends, injury reports, and accident hotspots.
- **Deliverables**: Screenshots and source files of visualizations are included.

---

### 🔍 Key Insights
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

### 🏆 Credits
This project is a part of the coursework for **Northeastern University** and was completed solely for academic purposes.

Feel free to contact the author for further details or suggestions.

---


