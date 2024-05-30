# Coffee Shop Sales Analysis

## Project Overview
Developed a Power BI project focused on analyzing sales data for a coffee shop. The project aims to construct a comprehensive dashboard that provides actionable insights into various aspects of sales performance, including total sales, order analysis, sales trends by time and location, and product performance.

## Problem Statement
The coffee shop is struggling to understand its sales performance. The specific areas of concern include:
<li>Total sales analysis</li>
<li>Total order analysis</li>
<li>Total quantity sold analysis</li>
<li>Sales analysis by weekdays and weekends</li>
<li>Sales analysis by store location</li>
<li>Daily sales with average line</li>
<li>Sales analysis by product category</li>
<li>Top 10 products by sales</li>
<li>Sales analysis by days and hours</li>
<li>The goal is to analyze these aspects to identify key drivers of sales and areas for improvement.</li>

## Tools Used
<li><b>MySQL:</b> For storing and querying sales data.</li>
<li><b>Excel:</b> For initial data cleaning and preparation.</li>
<li><b>Power BI:</b> For data visualization and exploratory data analysis (EDA).</li>

## Data Sources
<li><b>MySQL Database:</b> Contains sales data with columns including date, product, location, sales amount, quantity sold, order ID, etc.</li>
<li><b>Excel Files:</b> Used for additional data preparation and cleaning tasks.</li>

## Data Cleaning and Analysis
Data cleaning was performed in Excel and power bi to ensure data integrity and consistency before importing it into Power BI.

### Excel
<li><b>Changing Data Types:</b> Ensured that numeric columns (e.g., sales amount, quantity sold, order ID) were set to appropriate numeric data types.</li>
<li><b>Replacing Null Values:</b> Applied methods such as filling with mean/median for numeric fields.</li>
<li><b>Formatting Cells:</b> Ensured proper formatting for columns, such as setting number formats with appropriate decimal places.</li>
<li><b>Handling Missing Values:</b> Used Excel functions to fill or remove missing data.</li>
<li><b>Categorizing Products and Locations:</b> Ensured consistent labeling for products and locations.</li>
<li><b>Standardizing Date Formats:</b> Used Excel functions to convert date columns to a consistent format.</li>

### Power BI
<li><b>Data Modeling:</b> Created a date table and connected it with the transaction table using the date column as the common key. This allows for time-based analysis and filtering in the dashboard.</li>
<li><b>Conditional Formatting:</b> Used conditional formatting to highlight important data points and trends in the visualizations.</li>
<li><b>Data Validation:</b> Implemented data validation rules to ensure data quality and accuracy.</li>
<li><b>Data Transformation:</b> Utilized Power Query Editor to perform data cleaning operations such as removing duplicates, filtering rows, and transforming data types.</li>

### MySql & DAX:
Utilized MySql and DAX to make measures and calculations for Total sales, Total orders, Total quantity sold, Sales analysis by weekdays and weekends, Sales analysis by store location, Daily sales with average line, Sales analysis by product category, Sales analysis by days and hours


