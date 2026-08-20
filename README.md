 Airline Flight Performance & Operations Dashboard

 Dashboard Preview

 ✈️ AIRLINE OVERVIEW
 <img width="1416" height="800" alt="Overview" src="https://github.com/user-attachments/assets/2d7a96e8-98fb-410c-bbb1-1ca0b2e9214e" />

 📊 AIRLINE PERFORMANCE
 <img width="1426" height="795" alt="Airline   Performance" src="https://github.com/user-attachments/assets/aae65ec1-f4e8-4ba0-9012-4609a4e7ebd7" />

 🛫 ROUTE & AIRPORT MAP
 <img width="1420" height="803" alt="Route   Airport Map" src="https://github.com/user-attachments/assets/0836c284-8de8-4d00-b7a7-33d760d59f83" />

 🔍 DRILL THROUGH
 <img width="1420" height="806" alt="Drill-Through Detail" src="https://github.com/user-attachments/assets/90e8199a-151d-4ed6-a2dc-b756ec410640" />

  📈 TREND & FORECAST
  <img width="1410" height="800" alt="Trends   Forecast" src="https://github.com/user-attachments/assets/9d3aa35a-b9cd-48e4-8d54-4063d871eb1c" />

  💡 TOOLTIP
  <img width="1065" height="797" alt="Tooltip Airport" src="https://github.com/user-attachments/assets/2dd56cbb-230d-4adc-8d19-c0f6403d864d" />

  
📊 Project Overview

This project is an interactive Power BI Airline Performance Dashboard built to analyze flight operations, delays, cancellations, airline performance, airport activity, and historical trends.

The dashboard transforms flight-level data into an easy-to-use analytical report with KPI cards, slicers, bar charts, donut charts, maps, heatmaps, drill-through analysis, tooltips, and forecasting.

The main objective is to help users quickly answer questions such as:

How many flights were operated?

What is the overall on-time performance?

Which airlines have the highest number of cancellations?

Which airlines experience the highest average departure delays?

Which airports have the highest flight volume?

Which states have higher cancellation rates?

What are the major cancellation causes?

How has flight volume changed over time?

What does the future flight-volume trend look like?

🎯 Business Objectives

The dashboard focuses on four major analytical areas:

Overall Flight Operations – Monitor total flights, cancellations, delays, and on-time performance.

Airline Performance – Compare airlines using cancellation counts, cancellation rates, and average departure delays.

Airport & Route Analysis – Understand flight volume and cancellation performance geographically.

Trend & Forecast Analysis – Analyze monthly and yearly patterns and estimate future flight volume.

🖥️ Dashboard Pages

1. Overview

The Overview page provides a high-level summary of airline operations.

KPIs

Total Flights

Total Cancelled Flights

On-Time Rate

Cancellation Rate

Average Departure Delay

Average Arrival Delay

Visuals

Flight Cancellations by Cause – Donut chart showing cancellation reasons.

Flight Outcome Distribution – Donut chart comparing flight outcomes.

Overall On-Time Rate vs 80% Target – Gauge visual comparing actual performance with a target benchmark.

Filters / Slicers

The page includes interactive slicers for:

Airline

Delay Status

Flight Year

Additional flight-related filtering

These filters allow the entire dashboard to be explored dynamically.

2. Airline Performance

This page focuses on comparing airline-level performance.

Visuals

Top 10 Airlines by Cancellation Count

Identifies airlines with the highest number of cancelled flights.

Helps highlight airlines requiring further operational investigation.



Top 10 Airlines by Average Departure Delay

Compares airlines based on average departure delay in minutes.

Useful for identifying airlines with higher delay exposure.

Airline Cancellation Rate Heatmap by Year

Shows cancellation-rate patterns across airlines and years.

Makes year-over-year airline performance differences easier to identify.

Airline Performance Table

Provides detailed airline-level metrics including:

Total Flights

Cancellation Rate

On-Time Rate

Other relevant performance measures

This page also uses an Airline slicer for focused analysis.

3. Route & Airport Map

This page provides a geographical view of flight activity and cancellation performance.

US Departure Airports – Flight Volume and Avg Delay

A Bubble Map is used to analyze departure airports.

Location: Origin Airport

Bubble Size: Total Flights

Bubble intensity: Average Departure Delay

This makes it easy to identify airports with:

High flight volume

Higher average departure delays

US State Cancellation Rate Map

A Filled Map displays cancellation rates by US state.

This helps identify geographical areas with relatively higher or lower cancellation rates.

Filter

Flight Year slicer

4. Drill-Through Detail

The Drill-Through Detail page provides deeper analysis for a selected airline.

When a user selects an airline and drills through, the page provides airline-specific details.

KPIs

Total Flights for Selected Airline

Cancellation Rate for Selected Airline

Visuals

Total Cancelled by Flight Month

Monthly breakdown of cancelled flights.

Cancellation Reason

Donut chart showing cancellation causes for the selected airline.

Top 100 Origin by Arrival Delay

Detailed table containing:

Origin Airport

Destination Airport

Departure Delay

Arrival Delay

Flight Date

On-Time Rate Trend by Flight Year

Line chart showing how the selected airline's on-time rate changes over the years.

Power BI Concept Used

Drill-through filtering

Context-aware KPIs and visuals

Airline-specific detailed analysis

5. Trends & Forecast

This page focuses on historical flight trends and future projections.

Monthly Flight Volume by Year

A line chart compares monthly flight volume across different years.

Total Monthly Flight Volume – Trend & 6-Month Forecast

This visual combines:

Historical monthly flight volume

Trend analysis

6-month forecast

Forecast confidence boundaries

This helps identify expected future flight-volume movement.

Monthly Average Departure Delay by Year

A line chart compares monthly average departure delays across years.

Filter

Flight Month / Year based filtering

6. Tooltip – Airport

A dedicated report-page tooltip is used to provide additional airport information without overcrowding the main map.

The tooltip displays:

Total Flights

Cancellation Rate

Top Destination Airports

This improves the interactivity and readability of the Route & Airport Map.



📐 DAX & Data Analysis Concepts

The dashboard uses Power BI measures for dynamic calculations.

Core Measures

Total_flight

Calculates the total number of flight records in the current filter context.

Total_Cancelled

Calculates the number of cancelled flights using filter-based calculation logic.

Cancellation_Rate %

Calculates the percentage of flights that were cancelled.

On_Time_Rate

Calculates the percentage of flights meeting the defined on-time condition.

Avg_Dep_Delay

Calculates average departure delay.

Avg_Arr_Delay

Calculates average arrival delay.

Target_value

Provides the target benchmark used in the On-Time Rate gauge.

🔄 Power BI Features Used

This project demonstrates practical use of several Power BI concepts:

✅ Data modeling

✅ DAX measures

✅ Filter context

✅ CALCULATE-based calculations

✅ DIVIDE-based percentage calculations

✅ KPI cards

✅ Slicers

✅ Bar charts

✅ Line charts

✅ Donut charts

✅ Gauge chart

✅ Matrix / heatmap

✅ Table visual

✅ Bubble map

✅ Filled map

✅ Drill-through pages

✅ Report-page tooltips

✅ Conditional visual analysis

✅ Time-series analysis

✅ Forecasting

✅ Interactive page navigation

✅ Dynamic filtering

🗂️ Key Data Fields Used

The report uses flight-level fields such as:

AIRLINE

AIRLINE_CODE

ORIGIN

DEST

FL_DATE

Flight_Year

Flight_Month

Flight_Month_Start

DEP_DELAY

ARR_DELAY

CANCELLATION_CODE

Delay_Status

State

These fields support airline, airport, delay, cancellation, geographical, and time-series analysis.

📈 Key Business Insights Enabled

The dashboard allows stakeholders to identify:

Airlines with the highest cancellation volumes.

Airlines with higher average departure delays.

Changes in cancellation rates across years.

Airports handling the highest number of flights.

Airports associated with higher average departure delays.

States with comparatively higher cancellation rates.

Major cancellation causes.

Monthly and yearly flight-volume patterns.

Changes in on-time performance over time.

Expected future flight-volume trends through forecasting.

🎨 Dashboard Design

The report is designed with a clean, interactive dashboard structure so users can move from high-level KPIs → airline comparison → geographical analysis → detailed airline investigation → trends and forecasting.

The use of consistent navigation, slicers, drill-through functionality, and tooltips makes the report suitable for both quick management-level review and deeper operational analysis.

🛠️ Tools & Technologies

Tool

Purpose

Power BI Desktop

Dashboard development and visualization

DAX

Measures and analytical calculations

Power Query

Data preparation / transformation

Data Modeling

Relationships and analytical structure

Power BI Maps

Airport and state-level geographical analysis

Power BI Forecasting

Future flight-volume estimation

📁 Project Structure

Airline-Flight-Performance-Dashboard/
│
├── Project_5(1).pbix
├── README.md
└── Dashboard-Screenshot/
    └── dashboard-overview.png

🚀 How to Use

Download or clone this repository.

Open Project_5(1).pbix using Power BI Desktop.

Navigate through the dashboard pages using the page navigation buttons.

Use slicers to filter the analysis.

Select an airline to explore airline-specific performance.

Use Drill-through to open detailed airline analysis.

Hover over airport map points to view the custom tooltip.

Explore the Trends & Forecast page to understand historical patterns and future projections.

💡 Project Outcome

This project demonstrates how raw flight data can be converted into an interactive business intelligence solution using Power BI.

It combines data analysis, DAX, visualization, geographical analysis, drill-through, tooltips, and forecasting into a single dashboard designed for practical airline operations and performance analysis.

👩‍💻 Author

Disha Chaudhari

B.Sc. IT | Data Analytics / Power BI

Skills Demonstrated

Power BI DAX Power Query Data Visualization Data Analysis Data Modeling Business Intelligence Forecasting
