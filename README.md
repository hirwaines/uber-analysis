# 🚖 Uber Fares Data Analysis Dashboard

## 📘 Course: Introduction to Big Data Analytics (INSY 8413)
**Instructor:** Eric Maniraguha  
**Student:** HIRWA Ines  
**Tool Used:** Power BI Desktop  
**Dataset:** Uber Fares Dataset from Kaggle  
**Dashboard File:** `uber analysis.pbix`  
**Date:** July 2025

---

## 🎯 Objective

The purpose of this project was to explore and analyze the **Uber Fares Dataset** using Power BI. The assignment required performing **exploratory data analysis (EDA)**, applying **feature engineering**, and creating a clean, professional, and interactive **Power BI dashboard** that offers insights into fare trends, ride times, and passenger behavior.

---

## 🗂️ Dataset Overview

The dataset consists of information on Uber ride records, including:
- Fare amounts
- Pickup timestamps
- Passenger counts
- Geographic coordinates for pickup and dropoff

### ✅ Key Features Used:
- `fare_amount`
- `pickup_datetime`
- `hour`, `day`, `month`, `weekday`, `year` (engineered from pickup_datetime)
- `passenger_count`
- `peak_hour` (derived from hour)

---

## 🧼 Data Preparation Steps

1. Loaded the original dataset in Python.
2. Removed null values and duplicates.
3. Converted `pickup_datetime` to datetime format.
4. Engineered new time-based features (`hour`, `day`, `month`, etc.).
5. Created a `peak_hour` indicator (7–9 AM and 4–6 PM marked as "Yes").
6. Saved cleaned dataset as `uber_enhanced.csv`.

---

## 📊 Dashboard Overview

The dashboard is interactive and composed of multiple visuals to uncover meaningful patterns:

| Visual Title                    | Visual Type         | Description                                     |
|--------------------------------|---------------------|-------------------------------------------------|
| **Total Rides**                | Card                | Displays total number of Uber rides             |
| **Fare Amount Distribution**   | Column Chart        | Shows frequency of fares across price ranges    |
| **Rides per Hour**             | Column Chart        | Analyzes ride volumes during each hour          |
| **Rides by Weekday**           | Column Chart        | Shows trends across days of the week            |
| **Monthly Ride Trends**        | Line Chart          | Visualizes rides over months                    |
| **Peak vs Off-Peak Rides**     | Pie Chart           | Compares ride volumes during rush hours         |
| **Rides by Passenger Count**   | Bar Chart           | Shows how many passengers were in each ride     |
| **Slicer Filters**             | Slicer              | Filters by month, weekday, and peak hour        |




<img width="1377" height="705" alt="image" src="https://github.com/user-attachments/assets/057d7acb-16d9-4fac-8ca9-49f70513d862" />
Dashboard Metadata
Last saved timestamp shows recent activity (Today at 11:10 PM)

Contains standard Power BI tabs: Home, Insert, Modeling, View, Optimize, Help

Main Components
Data Acquisition:

Expanded data source options including Excel, OneLake, SQL Server, and Dataverse

"Transform Refresh data" option indicates ETL capabilities

Visualizations:

"Sum of fare amount by hour" chart showing distribution across hours (peaking at 100K)

"Count of key by month" chart displaying monthly trends (ranging 14K-18K)



<img width="1373" height="923" alt="image" src="https://github.com/user-attachments/assets/4e6b3370-6d2a-4aec-9928-6a646f7301a5" />
The image shows a hierarchical structure with multiple "Code" sections, suggesting this may represent a Power BI file or similar data analysis tool interface.

The sections appear to categorize different functionalities: data manipulation, data sources, visualization, and filtering.

Key Components
Data Operations: Includes basic functions like "Cuts", "Copy", and "Format painter", along with data-specific options like "Get data" from various sources (Excel, OneLake, SQL Server).

Visualization Tools: Contains options for creating new visuals, text boxes, and calculations (both visual and measure-based).

Filtering System: Shows filtering capabilities at both page-level and report-level, with fields for adding data filters.

Data Points:

Includes a "Peak_hour" field with binary options (Yes/No)

Shows "Count of key by peak" with values (55.79K) broken down by peak hour status

Displays date range data from "pickup_datetime" (1/1/2009 to 7/1/2015)

---

## 🔍 Insights & Analysis

- The majority of fares fall under \$30, indicating frequent short-distance rides.
- Most rides occur during peak commuting hours (7–9 AM and 4–6 PM).
- Weekdays show higher ride demand than weekends.
- One-passenger rides are the most common, showing Uber’s usage for solo travel.
- Monthly trends help visualize seasonality or ride surges.

---

## 📦 Project Deliverables

- ✅ `uber analysis.pbix`: Interactive Power BI Dashboard  
- ✅ `uber_enhanced.csv`: Cleaned and feature-engineered dataset  
- ✅ `README.md`: Project documentation  
- ✅ Screenshots (for report or presentation)



