# 📊 Power BI - Downtime Monitoring Dashboard

This project was built in **Power BI** with the purpose of monitoring and analyzing **downtime** based on several key factors:

- **Activity type** (e.g., maintenance, calibration, die change, etc.)
- **Priority level** (normal, urgent, high, very high, secondary)
- **Work area/asset** where the event occurred

⚠️ **Disclaimer:** The dataset used in this project is **fictitious**.  
This dashboard was created **only as a presentation model** and should not be interpreted as real operational data.

## 🗂️ Dataset
The dataset used comes from an **Excel file**, containing detailed records of work orders.  
The data includes:
- Activity type
- Event priority
- Recorded downtime
- Calendar period (date/month)
- Involved assets

## 📈 Key Features
The developed dashboard provides:
- Visualization of the **number of work orders** by activity
- Downtime analysis by **priority level**
- Trend of work orders over time (daily / monthly)
- Total aggregated downtime for the selected period
- Dynamic filters for:
  - Date range
  - Asset
  - Activity type
  - Priority

## 🖼️ Visual Example
Below is a snapshot of the Power BI dashboard:

![Dashboard Example](617ee05e-7510-4897-9bbe-155ad930791f.png)

## ▶️ How to Run
To reproduce or use this project in Power BI, follow these steps:

1. **Download the dataset**  
   - Ensure you have the Excel file containing the work orders dataset.

2. **Open Power BI Desktop**  
   - Install [Power BI Desktop](https://powerbi.microsoft.com/desktop/) if you don’t already have it.

3. **Load the dataset**  
   - Go to **Home > Get Data > Excel**  
   - Select the Excel file and import the required sheet(s).

4. **Data transformation (if needed)**  
   - Use the **Power Query Editor** to clean, filter, or transform columns (e.g., dates, activity types, priorities).

5. **Build the visuals**  
   - Create charts such as:
     - Donut chart: Work orders by activity type  
     - Donut chart: Work orders by priority  
     - Column chart: Work orders by day/month  
     - Card: Total downtime  

6. **Add slicers (filters)**  
   - Add slicers for Date, Asset, Activity Type, and Priority to make the report interactive.

7. **Publish or share**  
   - Save the report as `.pbix`  
   - Optionally, publish to the **Power BI Service** for online access and sharing.

## 🎯 Project Goal
The main objective of this application is to provide a clear overview of **downtime events** and support decision-making related to:
- Reducing downtime
- Identifying critical areas
- Prioritizing interventions based on impact
