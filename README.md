# ✈️ Airline Flight Performance & Operations Dashboard


# 📸 Dashboard Preview

✈️ AIRLINE OVERVIEW

<img width="1416" height="800" alt="Overview" src="https://github.com/user-attachments/assets/4056f73d-8019-4ed3-a35d-02887d0f045a" />

📊 AIRLINE PERFORMANCE

<img width="1426" height="795" alt="Airline   Performance" src="https://github.com/user-attachments/assets/b3fd5dad-caf9-4db0-a0ea-1b26a53353ea" />

🛫 ROUTE & AIRPORT MAP

<img width="1420" height="803" alt="Route   Airport Map" src="https://github.com/user-attachments/assets/47aa6d24-de82-462a-a0c9-420e21075512" />

🔍 DRILL THROUGH

<img width="1420" height="806" alt="Drill-Through Detail" src="https://github.com/user-attachments/assets/b90b619a-2ddc-4d22-87ab-4b601b4516eb" />

📈 TREND & FORECAST

<img width="1410" height="800" alt="Trends   Forecast" src="https://github.com/user-attachments/assets/6dae186a-7c43-4521-8cc5-42cea027d923" />


💡 TOOLTIP

<img width="1065" height="797" alt="Tooltip Airport" src="https://github.com/user-attachments/assets/d4836f0f-9c6c-4091-994b-27874f65679b" />


## 📊 Project Overview

This project is an interactive **Power BI Airline Performance Dashboard** developed to analyze flight operations, airline performance, delays, cancellations, airport activity, and historical trends.

The dashboard transforms flight-level data into an interactive business intelligence solution using **DAX, Power Query, KPI cards, slicers, charts, maps, drill-through analysis, report-page tooltips, and forecasting**.

### 🎯 Key Questions Answered

* How many flights were operated?
* What is the overall on-time performance?
* Which airlines have the highest number of cancellations?
* Which airlines have the highest average departure delays?
* Which airports have the highest flight volume?
* Which states have higher cancellation rates?
* What are the major cancellation causes?
* How does flight volume change over time?
* What is the expected future flight-volume trend?

---

## 🖥️ Dashboard Pages

### 1️⃣ Overview

The **Overview** page provides a high-level summary of overall airline operations.

#### 📌 KPIs

* Total Flights
* Total Cancelled Flights
* On-Time Rate
* Cancellation Rate
* Average Departure Delay
* Average Arrival Delay

#### 📊 Visualizations

* **Flight Cancellations by Cause** – Donut chart showing cancellation reasons.
* **Flight Outcome Distribution** – Donut chart showing flight outcomes.
* **Overall On-Time Rate vs 80% Target** – Gauge chart comparing actual performance with the target.

#### 🎛️ Filters

* Airline
* Delay Status
* Flight Year
* Other flight-related filters

---

### 2️⃣ Airline Performance

This page compares airline performance using different operational metrics.

#### 📊 Visualizations

**Top 10 Airlines by Cancellation Count**

* Identifies airlines with the highest number of cancelled flights.

**Top 10 Airlines by Average Departure Delay**

* Compares airlines based on their average departure delay.

**Airline Cancellation Rate Heatmap by Year**

* Shows cancellation-rate patterns across airlines and years.

**Airline Performance Table**

* Provides detailed airline-level performance information.

#### 📌 Metrics Analyzed

* Total Flights
* Cancellation Rate
* On-Time Rate
* Average Departure Delay
* Cancellation Count

An **Airline slicer** is also provided for interactive filtering.

---

### 3️⃣ Route & Airport Map

This page provides geographical analysis of flight activity and cancellation performance.

#### 🗺️ US Departure Airports – Flight Volume and Avg Delay

A **Bubble Map** is used to analyze departure airports.

* **Location:** Origin Airport
* **Bubble Size:** Total Flights
* **Bubble Intensity:** Average Departure Delay

This helps identify airports with high flight volume and higher average delays.

#### 🗺️ US State Cancellation Rate

A **Filled Map** displays cancellation rates by US state.

This helps identify geographical areas with relatively higher or lower cancellation rates.

#### 🎛️ Filter

* Flight Year

---

### 4️⃣ Drill-Through Detail

The **Drill-Through Detail** page provides detailed analysis for a selected airline.

When an airline is selected and the user performs a drill-through, airline-specific information is displayed.

#### 📌 KPIs

* Total Flights for Selected Airline
* Cancellation Rate for Selected Airline

#### 📊 Visualizations

**Total Cancelled by Flight Month**

* Monthly breakdown of cancelled flights.

**Cancellation Reason**

* Donut chart showing cancellation causes.

**Top 100 Origin by Arrival Delay**

* Detailed table containing:

  * Origin Airport
  * Destination Airport
  * Departure Delay
  * Arrival Delay
  * Flight Date

**On-Time Rate Trend by Flight Year**

* Line chart showing the selected airline's on-time performance over the years.

#### 🔄 Power BI Concept Used

* Drill-through filtering
* Context-aware KPIs
* Dynamic airline-specific analysis

---

### 5️⃣ Trends & Forecast

This page focuses on historical trends and future flight-volume projections.

#### 📈 Monthly Flight Volume by Year

A line chart compares monthly flight volume across different years.

#### 🔮 Total Monthly Flight Volume – Trend & 6-Month Forecast

This visual combines:

* Historical monthly flight volume
* Trend analysis
* 6-month forecast
* Forecast confidence boundaries

This helps understand expected future flight-volume movement.

#### 📉 Monthly Average Departure Delay by Year

A line chart compares monthly average departure delays across different years.

---

### 6️⃣ Airport Tooltip

A dedicated **Report Page Tooltip** is used to display additional airport information without overcrowding the main map.

The tooltip provides:

* Total Flights
* Cancellation Rate
* Top Destination Airports

This improves the interactivity and usability of the **Route & Airport Map**.

---

# 📐 DAX & Data Analysis

The dashboard uses DAX measures to perform dynamic calculations based on the current filter context.

### 🔹 Total Flights

Calculates the total number of flight records in the current filter context.

### 🔹 Total Cancelled

Calculates the total number of cancelled flights using filter-based calculation logic.

### 🔹 Cancellation Rate %

Calculates the percentage of flights that were cancelled.

### 🔹 On-Time Rate

Calculates the percentage of flights meeting the defined on-time condition.

### 🔹 Average Departure Delay

Calculates the average departure delay in minutes.

### 🔹 Average Arrival Delay

Calculates the average arrival delay in minutes.

### 🔹 Target Value

Provides the target benchmark used in the On-Time Rate gauge.

---

# 🔄 Power BI Concepts Used

This project demonstrates practical implementation of:

* ✅ Data Cleaning & Transformation
* ✅ Power Query
* ✅ Data Modeling
* ✅ DAX Measures
* ✅ Filter Context
* ✅ CALCULATE
* ✅ DIVIDE
* ✅ KPI Cards
* ✅ Slicers
* ✅ Bar Charts
* ✅ Line Charts
* ✅ Donut Charts
* ✅ Gauge Chart
* ✅ Matrix / Heatmap
* ✅ Tables
* ✅ Bubble Maps
* ✅ Filled Maps
* ✅ Drill-Through
* ✅ Report Page Tooltips
* ✅ Conditional Analysis
* ✅ Time-Series Analysis
* ✅ Forecasting
* ✅ Interactive Navigation
* ✅ Dynamic Filtering

---

# 🗂️ Key Data Fields

The dashboard uses flight-level fields including:

* `AIRLINE`
* `AIRLINE_CODE`
* `ORIGIN`
* `DEST`
* `FL_DATE`
* `Flight_Year`
* `Flight_Month`
* `Flight_Month_Start`
* `DEP_DELAY`
* `ARR_DELAY`
* `CANCELLATION_CODE`
* `Delay_Status`
* `State`

These fields support airline, airport, delay, cancellation, geographical, and time-series analysis.

---

# 📈 Business Insights

The dashboard enables users and business stakeholders to identify:

* Airlines with the highest cancellation volumes.
* Airlines experiencing higher average departure delays.
* Changes in cancellation rates across different years.
* Airports handling the highest number of flights.
* Airports associated with higher average departure delays.
* States with comparatively higher cancellation rates.
* Major cancellation causes.
* Monthly and yearly flight-volume patterns.
* Changes in airline on-time performance.
* Expected future flight-volume trends using forecasting.

---

# 🎨 Dashboard Design

The dashboard follows an interactive analytical flow:

**Overview → Airline Performance → Route & Airport Analysis → Drill-Through Details → Trends & Forecast**

Interactive slicers, drill-through functionality, maps, tooltips, and forecasting allow users to move from high-level KPIs to detailed airline and airport analysis.

The report is designed to be **clean, interactive, easy to navigate, and suitable for business intelligence analysis**.

---

# 🛠️ Tools & Technologies

| Tool / Technology        | Purpose                                 |
| ------------------------ | --------------------------------------- |
| **Power BI Desktop**     | Dashboard development and visualization |
| **DAX**                  | Analytical calculations and measures    |
| **Power Query**          | Data cleaning and transformation        |
| **Data Modeling**        | Structuring data for analysis           |
| **Power BI Maps**        | Geographical analysis                   |
| **Power BI Forecasting** | Future trend analysis                   |

---

# 📁 Project Structure

```text
Airline-Flight-Performance-Dashboard/
│
├── Project_5(1).pbix
├── README.md
└── Dashboard-Screenshot/
    └── dashboard-overview.png
```

---

# 🚀 How to Use

1. Download or clone this repository.
2. Open `Project_5(1).pbix` using **Power BI Desktop**.
3. Navigate through the dashboard pages.
4. Use the available slicers to filter the data.
5. Select an airline to analyze airline-specific performance.
6. Use **Drill-Through** to view detailed airline analysis.
7. Hover over airport map points to view the custom tooltip.
8. Open the **Trends & Forecast** page to analyze historical and future trends.

---

# 💡 Project Outcome

This project demonstrates how raw airline flight data can be transformed into an **interactive Business Intelligence dashboard using Microsoft Power BI**.

The project combines:

**Data Analysis + DAX + Power Query + Data Visualization + Data Modeling + Geographical Analysis + Drill-Through + Tooltips + Forecasting**

to create a complete airline performance analytics solution.

---

## 👩‍💻 Author

### Disha Chaudhari

**B.Sc. IT | Data Analytics / Power BI**

### Skills Demonstrated

`Power BI` `DAX` `Power Query` `Data Analysis` `Data Visualization` `Data Modeling` `Business Intelligence` `Forecasting`

---

⭐ **If you find this project useful, feel free to star the repository!**
