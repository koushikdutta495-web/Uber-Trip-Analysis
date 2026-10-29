# 🚕 Uber Trip Analysis Dashboard | Power BI

## 📌 Project Overview

The **Uber Trip Analysis Dashboard** is an interactive Power BI project designed to analyze trip bookings, fare revenue, trip distance, travel duration, vehicle usage, pickup and drop-off locations, and time-based booking patterns.

The dashboard helps users explore ride-booking data, understand customer travel patterns, compare vehicle categories, and identify important trends across locations and time periods.

## 🎯 Business Objectives

The main objectives of this project are to:

- Monitor total trip bookings and booking value.
- Analyze average fare value, trip distance, and trip duration.
- Compare booking patterns across vehicle types.
- Identify frequently used pickup and drop-off locations.
- Understand trip demand by pickup hour and day.
- Explore trip details for more granular analysis.

## 🛠️ Tools & Technologies

- **Microsoft Power BI** — Dashboard development and data visualization
- **Power Query** — Data preparation and transformation
- **DAX** — KPI calculations and dynamic measures
- **Data Modeling** — Relationships between trip, location, and calendar data
- **Interactive Reporting** — Filters, dynamic titles, and report navigation

## 📂 Dataset Information

The main data table is `Trip Details`, supported by location and calendar tables.

Important columns include:

- `Trip ID`
- `passenger_count`
- `trip_distance`
- `PULocationID`
- `DOLocationID`
- `fare_amount`
- `Surge Fee`
- `Vehicle`
- `Payment_type`
- `Pickup Date`
- `Pickup Time`
- `Drop Off Date`
- `Drop Off Time`
- `Duration`
- `Trip Type`
- `Pickup Hours`

The `Location Table` provides location names and city information. The calendar tables support date-based analysis.

*Note: The project template identifies the fields used in the analysis, but the original dataset's publisher, licensing, and exact reporting period have not been independently verified.*

## 📊 Key Performance Indicators (KPIs)

The dashboard includes DAX measures for the following metrics:

| KPI | Description |
|---|---|
| Total Booking | Distinct count of Trip IDs |
| Total Booking Value | Sum of fare amounts |
| Average Booking Value | Average fare amount |
| Total Trip Distance | Aggregated trip distance |
| Average Trip Distance | Average trip distance |
| Average Trip Time | Average trip duration in minutes |
| Most Frequent Pickup Point | Pickup location with the highest booking count |
| Most Frequent Drop-off Point | Most frequently used drop-off location |
| Farthest Trip | Pickup and drop-off locations of the longest trip |

## 📈 Dashboard Pages

### 1. Overview Analysis

Provides a high-level view of Uber trip activity, including booking performance, fare value, vehicle-related analysis, and pickup/drop-off location insights.

Key analytical areas:
- Overall booking and fare metrics
- Vehicle type distribution
- Pickup and drop-off location analysis
- Trip performance comparisons
- Summary-level trip insights

### 2. Time Analysis

Focuses on understanding how trip activity changes throughout the day and across different dates.

Key analytical areas:
- Pickup-hour analysis
- Day-of-week booking patterns
- Time-based trip trends
- Dynamic metric analysis by pickup time and day
- Comparison of trip activity across selected periods

### 3. Details

Provides a detailed view of individual trip records for more granular analysis.

The detailed table supports exploration of trip-level information, including available trip, vehicle, fare, distance, and location fields.

## 🔍 Interactive Features

- Date-based analysis using calendar fields
- Vehicle and trip-related filtering
- Location-based exploration
- Dynamic titles and metric selection
- Detailed trip-level inspection
- Navigation between report pages

*The available filters and interactions depend on the controls implemented in the final report.*

## 💡 Business Questions Explored

This dashboard is designed to help investigate questions such as:

- How many trips were booked during the selected period?
- What is the total and average fare value?
- Which vehicle category contributes the most bookings?
- Which locations are the most frequently used for pickups and drop-offs?
- At what times or on which days is trip activity higher?
- What are the average trip distance and duration?
- Which trip has the greatest recorded distance?

## 💼 Business Value

The analysis demonstrates how trip-level data can be transformed into an interactive reporting solution to support:

- Ride-demand monitoring
- Vehicle category comparison
- Pickup and drop-off location analysis
- Time-based demand planning
- Trip performance monitoring
- Data-driven operational decisions

These are potential applications of the dashboard; specific business improvements would need to be validated using actual analysis results.

## 🧠 Skills Demonstrated

- Data analysis and business question development
- Power BI dashboard design
- DAX measure creation
- Data modeling and relationship management
- Time-based analysis
- Location-based analysis
- KPI reporting and interactive visualization

## 📷 Dashboard Preview

Add screenshots of your actual Power BI report to the repository and update the filenames below.

### Overview Analysis
![Uber Overview Analysis](screenshots/uber-overview-analysis.png)

### Time Analysis
![Uber Time Analysis](screenshots/uber-time-analysis.png)

### Details
![Uber Trip Details](screenshots/uber-trip-details.png)



## 🚀 Project Outcome

This project demonstrates practical skills in using Power BI, DAX, data modeling, and interactive visualization to explore ride-booking data and communicate operational insights.

It is part of my ongoing journey to strengthen my practical data analytics skills and build a professional Data Analyst portfolio.


