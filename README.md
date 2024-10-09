# Power BI Visualizations

## Introduction
This repository contains a collection of Power BI visualizations developed during my internship. The reports focus on analyzing sales data trends, providing insights, and enabling informed decision-making. The visuals offer interactive elements, such as filters and drilldowns, allowing users to explore the data more thoroughly.

### Visuals Overview

---

### 1. **Volumes Monthly Detail Report**
![Volumes Monthly Detail Report](images/Volumes_Monthly_Detail.png)
- **Description:** This report provides an in-depth analysis of total sales volume and revenue over a three-year period (2022-2024). Users can examine monthly trends, state-based insights, and explore the data interactively.
  
- **Key Features:**
  - **KPI Cards:** 
    - **Monthly Revenue KPI**: Displays the total revenue for the selected month.
    - **Monthly Volume KPI**: Shows the total volume for the current month and compares it with the previous month’s volume for trend analysis.
  - **Stacked Column Chart:** Visualizes volume trends by month and category (e.g., type, subtype).
  - **US Map:** Enables users to click on a specific state to filter other visuals, such as charts that show data by state or location. When hovering over a state, a tooltip appears displaying:
    - **State Name:** The name of the state you are hovering over.
    - **Volume Over Time:** A small line graph showing the volume trends over time for the selected state, allowing users to quickly assess performance without having to click into the state.
  - **Navigation Panel:** A left-side panel allows users to easily switch between different pages of the report. 
    - **Main Page**: Shows high-level metrics like volume by category and type, volume and revenue by month, and volume by state and region.
    - **Map Page**: Offers a detailed state-by-state view with site-specific breakdowns when a state is selected.
  - **Interactivity:** Clicking a state in the map updates all other visuals to display only data related to that state.
![Volumes Monthly Detail Map Page](images/volumes_monthly_detail_map.png)

---

### 2. **Weekly Trends Analysis**
![Weekly Trends Analysis](images/volumes_weekly.png)
- **Description:** This report focuses on analyzing weekly volume trends over a three-year period, helping identify patterns, anomalies, and shifts in sales across different time frames.
  
- **Key Features:**
  - **KPI Card:**
    - **Weekly Volume KPI:** Displays the total volume for the selected week and compares it to the previous week's volume for quick trend analysis.
  - **Weekly Volume Line Chart:** Plots weekly volume trends. Yellow dots highlight anomalies in the data—unexpected spikes or dips. To the right of the chart, the leading factor causing each anomaly is displayed, offering context behind the change.
  - **State-by-Volume Map:** Enables users to select states to filter the data for specific regions.
  - **Location Name Selector:** Filters visuals based on specific site locations, allowing users to drill down into the data for individual locations.

---


## How to Use the Reports

Each of these reports offers various interactive features, allowing users to explore and analyze data in different ways:
- **Filtering:** Click on a state in the maps or use the location selectors to filter the charts by specific regions or sites.
- **Drilldowns:** Select a time period (week, month, or year) to explore trends over different intervals.
- **KPI Comparison:** The KPI cards allow you to quickly compare the current period's data with the previous period, making it easy to spot changes in trends.
- **Anomaly Detection:** Look for yellow dots in the Weekly Trends Line Chart, which highlight anomalies. These help identify significant deviations in volume patterns, with possible causes displayed to the right.

---

## Data Sources
- **Volumes Monthly Detail Report:** Data includes fields such as volume, category, type (E=Temp event, F=Fixed location, etc.), subtype (H=Host, M=Corporate, etc.), location name, year, month, state, region, and revenue.
- **Weekly Trends Report:** Includes similar fields as the Monthly Report but focuses on weekly granularity. The report includes weekly volume and anomaly detection features.

---

## Screenshots

### Volumes Monthly Detail Report
![Volumes Monthly Detail Report](screenshots/volumes_monthly_detail_report.png)

### Weekly Trends Analysis
![Weekly Trends Analysis](screenshots/weekly_trends_analysis.png)

---

## Repository Contents

- **README.md**: Detailed explanations of the Power BI reports, their key features, and usage instructions.
- **Images**: Contains images of the Power BI dashboards for reference.

---
