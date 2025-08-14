# Cab Service Data Analysis & Dashboard Project
![Logo](/Images/logo.png)

## 1. Overview
This project presents an in-depth analysis of a cab service company's operational and passenger data. The primary objective is to uncover key business insights, track performance against targets, and provide actionable recommendations through interactive dashboards. The analysis focuses on overall business performance, revenue metrics, and passenger behavior, including customer acquisition and retention.

This entire analysis was conducted using Microsoft Excel, leveraging its advanced data tools like Power Query for ETL, Power Pivot for data modeling, and DAX for complex calculations.

## 2. Tools Used
Microsoft Excel: Core tool for the entire project.

Power Query: For performing Extract, Transform, Load (ETL) operations. Used to connect to the data source, clean, transform, and shape the data for analysis.

Power Pivot: For creating a robust and relational data model. It allowed for the integration of multiple data tables and the creation of complex relationships.

DAX (Data Analysis Expressions): For creating powerful calculated columns and measures to derive deep analytical insights that were not available in the raw data.

## 3. Steps
The project followed a structured data analysis process:

Data Extraction & Transformation (ETL): Raw data was loaded into Excel's Power Query Editor. Here, it was cleaned to handle missing values and inconsistencies, transformed to fit the analysis requirements, and new conditional columns were added.

Data Modeling: The cleaned data was loaded into Power Pivot to create a relational star schema. This model connects fact tables (like trip and passenger summaries) with dimension tables (like city and date), creating a single source of truth and enabling efficient analysis across different business aspects.

DAX Calculations: Numerous DAX measures and calculated columns were created to quantify Key Performance Indicators (KPIs). Key calculations include:

Summary Metrics: Total Revenue, Total Distance, Total Trips, Average Driver Rating.

Passenger Metrics: Total Passengers, Repeat Passengers, New Passengers, Repeat Passenger Rate (RPR).

Target Analysis: New Passengers Target Achieved %, Total Trips Target Achieved %.

Calculated Columns: Day Type (Weekday/Weekend), Month Name, etc.

Dashboard Visualization: Two interactive dashboards were built in Excel to present the findings in a clear, concise, and visually engaging manner. Slicers for city_name and Month Name were added to allow for dynamic filtering and deep-dive analysis.

## 4. Data Model
The data model forms the backbone of this analysis, linking various data tables to allow for comprehensive insights. The model consists of fact tables containing transactional data and dimension tables providing descriptive context.

![Model](/Images/Model.png)

Key Tables in the Model:

fact_trip: Contains detailed records for each trip.

fact_passenger_summary: A summary table for passenger metrics.

dim_city: Dimension table with city information.

dim_date: A date dimension table for time-based analysis.

monthly_target_merged: Contains monthly targets for trips and new passengers.

city_target_passenger_rating: Holds the target passenger rating for each city.

## 5. Dashboards & Key Insights
Two distinct dashboards were created to cater to different analytical needs: a high-level summary and a detailed passenger analysis.

### 5.1. Summary Dashboard
This dashboard provides a 360-degree view of the company's overall performance.

![Summary](/Images/Summary.png)

### 5.2. Passenger Analysis Dashboard
This dashboard focuses on customer-centric metrics, specifically analyzing new vs. repeat passenger behavior.

![Passangers](/Images/Passangers.png)

## 7. Conclusion
This analysis provides critical insights into the cab service's operations and customer dynamics. The company demonstrates strong performance in revenue and trip volume, particularly in key urban centers. The positive trend in repeat passengers is a healthy sign of customer loyalty.
