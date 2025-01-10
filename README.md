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

### Phase 2: Integration and Transformation
- **ETL Workflow**: **Talend pipelines** were created to process staging data into the integrated layer.
- **Validation**: SQL queries ensured the accuracy of transformations and provided explanations for rejected records.
- **Advanced Modeling**: The inclusion of **Slowly Changing Dimensions (SCDs)** and **Factless Facts** supported additional business requirements.

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

## Credits
This project was developed as part of a course at **Northeastern University** and is solely for academic purposes.

---
