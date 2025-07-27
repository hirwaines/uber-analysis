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



