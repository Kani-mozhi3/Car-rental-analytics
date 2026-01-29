# Car Rental Analytics
   A compact data analytics project showcasing SQL Server, data cleaning, and interactive Power BI reporting on a car rental business dataset.

## Project Overview
This project analyzes 500 cars from VEERA SERVICES with details such as price, brand, model, fuel type, color, transmission status, and yearly sales.
​
The goal is to demonstrate an end‑to‑end analytics workflow: loading raw data, cleaning and transforming it, querying with SQL Server, and visualizing insights in Power BI.


## Dataset Description
The dataset represents sales information of a fictional car rental provider.

 -<a href="https://github.com/Kani-mozhi3/Car-rental-analytics/blob/main/Data.xlsx">Dataset</a>​

Key fields (example):

CarID, Brand, Model, Color

FuelType (Petrol, Diesel, Electric, CNG, Hybrid)
​

TransmissionStatus (Active, Expired)
​

Year, Price, SalesAmount

### The sample dashboard shows: total cars (500), total price (13.41K units), 10 brands, 10 models, and 5 fuel types.
​

## Tech Stack
Database: Microsoft SQL Server for data storage, cleaning, and KPI calculation.

Visualization: Microsoft Power BI for interactive reports and drill‑down analysis.

Other: Power Query for additional transformations before loading to the data model.

## Project Workflow

### 1.Data Loading

-Create database and tables in SQL Server for car, pricing, and sales data.

-Bulk insert or import the dataset (CSV/Excel) into the staging tables.

### 2.Data Cleaning & Transformation

-Standardize categorical values (colors, brands, fuel types).
​
-Handle missing or duplicate records and validate numeric columns (price, sales).

-Move clean data from staging to production tables.

### 3.SQL Analysis

-Aggregate metrics such as total cars, average price per brand, and count by fuel type.
​

-Create views/stored procedures to serve as a reliable data source for Power BI.

### 4.Power BI Modeling & Visualization

-Connect Power BI to SQL Server views.

-Build measures for KPIs (total cars, revenue, % by fuel, % by status).

## Key KPIs and Insights
-Total cars in fleet and cumulative price.
​
-Number of brands, models, and fuel types offered.
​
-Car distribution by color and fuel type for inventory decisions.​

-Year‑wise total sales with share of each year.
​
-Transmission status split between Active and Expired vehicles.

## Use Cases for Recruiters
Quickly evaluate my hands‑on skills with SQL Server, Power Query, and Power BI in a realistic business scenario.

Review my approach to data cleaning, KPI definition, and dashboard storytelling from raw data to insights.


##Dashboard

<img width="1233" height="673" alt="Car" src="https://github.com/user-attachments/assets/c819594a-6ab6-4bb9-87a0-4f10a69eb03e" />
