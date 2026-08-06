<p align="center">
<img width="1774" height="887" alt="cover image" src="https://github.com/user-attachments/assets/0f2b4b67-b3a3-4d08-b627-24dc6062f844" />
</p>

---

<div align="center">
An end-to-end Business Intelligence project that demonstrates data preprocessing, transformation, modeling, visualization, and insight generation using Real-Time Air Quality data.

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Microsoft%20Excel-Data%20Cleaning-217346?logo=microsoftexcel&logoColor=white)
![Power Query](https://img.shields.io/badge/Power%20Query-Transformation-742774)
![DAX](https://img.shields.io/badge/DAX-Measures%20%26%20Calculated%20Columns-blue)
![GitHub](https://img.shields.io/badge/GitHub-Portfolio-black?logo=github)

</div>

---

# 📑 Table of Contents

- Project Overview
- Project Objectives
- Tools & Technologies
- Dataset Information
- Excel Data Preprocessing
- Power Query Transformations
- Data Modeling
- DAX Measures
- Calculated Columns
- Dashboard Pages
- Key Insights
- Recommendations
- Skills Demonstrated
- Repository Structure
- How to Use
- Project Outcome
- Author

---

# 📌 Project Overview

The **Real-Time Air Quality Analysis Dashboard** is an end-to-end Business Intelligence project developed using Excel and Power BI. The project focuses on analyzing air quality data collected from monitoring stations across different states and cities in India.

The workflow begins with **data preprocessing in Excel**, where the dataset was inspected, cleaned, standardized, and validated. The cleaned dataset was then imported into **Power BI**, where **Power Query** was used for further transformation and preparation. Interactive visualizations were created using DAX Measures, Calculated Columns, KPI cards, maps, slicers, and drill-through functionality to enable meaningful analysis.

The dashboard helps users compare pollution levels across different states, cities, and pollutant types while providing actionable insights for environmental monitoring and decision-making.

---

## 📌 Project Highlights

✔ Excel Data Preprocessing

✔ Power Query Transformation

✔ Interactive Power BI Dashboard

✔ DAX Measures & Calculated Columns

✔ Drill Through Functionality

✔ KPI Cards

✔ Interactive Filters & Slicers

✔ Business Insights & Recommendations

---

# 🎯 Project Objectives

- Perform data preprocessing using Microsoft Excel.
- Clean and validate the air quality dataset.
- Apply Power Query transformations.
- Create DAX Measures and Calculated Columns.
- Build an interactive multi-page Power BI dashboard.
- Analyze pollutant distribution across India.
- Compare air quality across states and cities.
- Generate meaningful insights and recommendations.
- Demonstrate an end-to-end Business Intelligence workflow.

---

# 🛠 Tools & Technologies

| Tool | Purpose |
|------|---------|
| Microsoft Excel | Data Cleaning & Preprocessing |
| Microsoft Power BI | Dashboard Development |
| Power Query | Data Transformation |
| DAX | Measures & Calculated Columns |
| GitHub | Project Documentation |

---

# 📂 Dataset Information

**Dataset Name**

Real-Time Air Quality Index from Various Locations

### Dataset Features

- Country
- State
- City
- Station
- Last Update
- Pollutant ID
- Pollutant Minimum
- Pollutant Maximum
- Pollutant Average
- Latitude
- Longitude

The dataset contains real-time environmental monitoring data collected from multiple monitoring stations across India. It includes pollutant measurements and geographical information that enable spatial and comparative analysis.

---

# 🧹 Excel Data Preprocessing

Data preprocessing was carried out in Microsoft Excel before importing the dataset into Power BI.

### Steps Performed

### 1. Dataset Inspection

- Examined dataset structure
- Reviewed column names
- Verified data types
- Identified data quality issues

### 2. Duplicate Check

- Checked duplicate records using Excel's Remove Duplicates feature.
- No duplicate records were found.

### 3. Missing Value Handling

Missing values were identified in:

- pollutant_min
- pollutant_max
- pollutant_avg

Incomplete records were removed to maintain data accuracy and reliability.

### 4. Removing Unnecessary Spaces

The **TRIM()** function was applied to remove leading and trailing spaces from the Station column.

### 5. Date Standardization

The **Last Update** column was formatted into a consistent date-time format.

**Format Used**

```
dd-mm-yyyy hh:mm
```

### 6. Location Column

A new **Location** column was created by combining the Country and State columns.

### 7. Filtering

Excel filters were applied to all columns for easier verification and analysis.

### 8. Sorting

The dataset was sorted by:

- Country
- State
- City
- Last Update

This improved dataset organization before analysis.

### 9. Calculated Field

A new calculated field named **Pollution Range** was created using:

```
Pollution Range = pollutant_max − pollutant_min
```

### 10. Excel Table

The cleaned dataset was converted into an Excel Table to improve data management and compatibility with Power BI.

### 11. Pivot Table

A Pivot Table was created to calculate the **Average Air Quality by State**.

A Pivot Chart was also generated to visualize the summarized information.

### 12. Conditional Formatting

A three-color scale was applied to the **Pollution Range** column to highlight low, medium, and high pollution ranges visually.

---

# ⚡ Power Query Transformations

After importing the cleaned dataset into Power BI, additional transformations were performed using Power Query.

### Transformations Performed

- Verified and corrected data types
- Renamed columns for better readability
- Removed unnecessary formatting inconsistencies
- Checked for null values after import
- Applied transformation steps
- Loaded the transformed dataset into the Power BI data model
---

# 🔗 Data Modeling

The dataset was modeled in Power BI to support efficient analysis and interactive reporting.

### Data Modeling Activities

- Imported the cleaned dataset into Power BI.
- Verified relationships between tables.
- Optimized data types for analysis.
- Created DAX Measures and Calculated Columns.
- Built an efficient model for dashboard visualization.

---

# 📐 DAX Implementation

DAX (Data Analysis Expressions) was used to create measures and calculated columns that enhanced dashboard functionality and enabled dynamic analysis.

## Measures

The following measures were created to summarize and analyze the data:

- Average Air Quality
- Total States
- Total Cities
- Total Monitoring Stations
- Additional KPI measures used in dashboard cards

These measures provide quick insights into the dataset and support interactive reporting.

---

## Calculated Columns

Calculated columns were created to improve analysis and categorization.

Examples include:

- Pollution Range
- Air Quality Status
- Additional derived columns for dashboard analysis

---

# 🚀 Dashboard Features

The dashboard includes the following interactive components:

- KPI Cards
- Clustered Bar Chart
- Clustered Column Chart
- Donut Chart
- Pie Chart
- Funnel Chart
- Treemap
- Interactive Map
- Top 10 Analysis
- Slicers
- Drill Through
- Multi-page Navigation

---

# 📊 Dashboard Pages

The Power BI dashboard consists of three interactive report pages along with a Drill Through page.

## 📄 Page 1 – Dashboard Overview

<p align="center">
<img width="1372" height="738" alt="dashboard_page1" src="https://github.com/user-attachments/assets/704cc8eb-ae99-4d4d-9d82-7b496d1e3de2" />
</p>

This page provides a high-level overview of air quality across India.

### Features

- KPI Cards
- Average Air Quality by State
- Average Pollutant by Pollutant Type
- Pollutant Distribution
- Interactive Map
- State Slicer
- City Slicer

Users can quickly identify pollution trends across different regions.

---

## 📄 Page 2 – Air Quality Analysis

<p align="center">
<img width="1370" height="740" alt="dashboard_page2" src="https://github.com/user-attachments/assets/e11a9371-6c74-4cca-aeaa-ee8af556cd9a" />
</p>

This page provides a deeper analysis of pollutant levels and geographical distribution.

### Features

- Treemap
- Donut Chart
- Top 10 Cities Analysis
- Comparative Charts
- Interactive Filtering
- Funnel Chart

The page enables detailed comparison between pollutant types, cities, and states.

---

## 📄 Page 3 – Insights & Recommendations

<p align="center">
<img width="1296" height="735" alt="Screenshot 2026-08-06 160149" src="https://github.com/user-attachments/assets/32d94359-40fc-47df-910e-4ecb1d41ed9e" />
</p>

This page summarizes the major findings obtained from the dashboard.

It includes:

- Key Insights
- Business Recommendations
- Dashboard Summary

The purpose of this page is to convert analytical findings into actionable recommendations.

---

## 📄 Drill Through Page

A dedicated Drill Through page was created to provide detailed information for selected locations.

Users can:

- View location-specific details
- Analyze pollutant information
- Navigate back to the main dashboard

This feature enhances interactivity and enables deeper exploration of the dataset.

---

# 💡 Key Insights

Based on the dashboard analysis, the following insights were identified:

- **PM2.5 is the most frequently monitored pollutant**, accounting for the highest proportion of pollutant records in the dataset.
- **PM10 recorded the highest average pollutant value**, indicating higher concentration levels compared to other pollutants.
- Air quality varies across different states and cities, showing significant regional differences in pollution levels.
- The dashboard identifies pollution hotspots, enabling users to compare locations and pollutant trends effectively.
- Interactive slicers and drill-through functionality provide detailed analysis by state, city, and monitoring station.

---

# ✅ Recommendations

Based on the analysis, the following recommendations are suggested:

- Prioritize pollution control measures for **PM2.5** and **PM10**, as they have the greatest impact on air quality.
- Strengthen environmental monitoring in highly polluted states and cities.
- Expand monitoring stations in regions with limited air quality coverage.
- Regularly update the dashboard with new data for continuous monitoring and decision-making.
- Utilize dashboard insights to support environmental planning, policy formulation, and public awareness initiatives.

---

# 🎓 Skills Demonstrated

This project demonstrates practical knowledge in:

- Microsoft Excel
- Data Cleaning
- Data Validation
- Data Preprocessing
- Power Query
- Data Transformation
- Data Modeling
- DAX Measures
- Calculated Columns
- Power BI Dashboard Development
- Interactive Reporting
- KPI Design
- Map Visualization
- Drill Through
- Data Visualization
- Business Intelligence
- Insight Generation
- GitHub Documentation

---
# 📁 Repository Structure

```text
Real-Time-Air-Quality-Analysis/
│
├── README.md
├── Air Quality Dashboard.pbix
├── Air_Quality_Cleaned.xlsx
├── dashboard_page1.png
├── dashboard_page2.png
└── dashboard_page3.png
```
---
# 🚀 How to Use

1. Clone or download this repository.
2. Open the Air Quality Dashboard.pbix file in Microsoft Power BI Desktop.
3. Use the slicers, filters, and drill-through functionality to explore the dashboard.
4. Review the Insights & Recommendations page for the key findings.
   
---

# 📈 Project Outcome

This project successfully demonstrates an end-to-end Business Intelligence workflow using Microsoft Excel and Power BI. The dashboard transforms raw air quality data into meaningful visualizations and actionable insights through data preprocessing, Power Query transformations, DAX calculations, and interactive reporting.

The project enables users to:

- Monitor air quality across different regions.
- Compare pollutant levels by state and city.
- Identify pollution trends and hotspots.
- Support informed environmental decision-making through interactive analytics.

---

# 👨‍💻 Author

## Gayathri S Pillai

**MBA Graduate | Business Analytics & Marketing**

📊 Aspiring Data Analyst | Power BI | Excel | Business Intelligence

📧 Email: gayathrispillai2015@gmail.com

💼 LinkedIn: https://www.linkedin.com/in/gayathri-s-pillai21

<div align="center">

⭐ Thank you for visiting my project repository!

</div>
