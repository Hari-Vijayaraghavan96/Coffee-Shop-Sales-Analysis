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
Data cleaning was performed in Excel and transformed into power bi power query to ensure data integrity and consistency.

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

### MySql & DAX
Utilized MySql and DAX to make measures and calculations for Total sales, Total orders, Total quantity sold, Sales analysis by weekdays and weekends, Sales analysis by store location, Daily sales with average line, Sales analysis by product category, Sales analysis by days and hours.

## Visualization Used in Power BI
<li><b>Total Sales Analysis:</b> Card and line chart to visualize total sales over different time periods.</li>
<li><b>Total Order Analysis:</b> Card and line chart to show the number of orders over different time periods.</li>
<li><b>Total Quantity Sold Analysis:</b> Card and line chart to display the total quantity of products sold.</li>
<li><b>Sales Analysis by Weekdays and Weekends:</b> pie chart to compare sales on weekdays versus weekends.</li>
<li><b>Sales Analysis by Store Location:</b> Bar chart to show sales performance by location.</li>
<li><b>Daily Sales with Average Line:</b> Column chart with an average line to show daily sales trends.</li>
<li><b>Sales Analysis by Product Category:</b> Bar chart to display sales distribution across different product categories.</li>
<li><b>Top 10 Products by Sales:</b> Bar charts to highlight the top 10 products based on sales.</li>
<li><b>Sales Analysis by Days and Hours:</b> Matrix chart to analyze sales performance across different days and hours.</li>
<li><b>Calendar map for monthly and daywise:</b> Matrix chart used to filter analysis based on month and day.</li>
<li><b>Tooltip in calender map and days & hours chart</b> Implemented tooltip for the calendar map and matrix chart to display detailed information when hovering over each day and hour for analysis.</li>

## Exploratory Data Analysis (EDA)
<li>What are the total sales and sales trends over different time periods?</li>
<li>How do the total orders and quantity sold vary over time?</li>
<li>What are the sales patterns on weekdays versus weekends?</li>
<li>How does sales performance vary across different store locations?</li>
<li>What are the daily sales trends, and how do they compare to the average sales?</li>
<li>Which product categories contribute the most to sales?</li>
<li>Which are the top 10 products by sales?</li>
<li>How does sales performance vary by days and hours?</li>

## Result
![image](https://github.com/Hari-Vijayaraghavan96/Coffee-Shop-Sales-Analysis/assets/163993617/8072950b-9045-4817-ad46-31299bb68ca3)

## Recommendations
Based on the analysis, the following insights and recommendations were derived:
<li><b>Optimize Product Mix:</b> Focus on high-performing products and consider phasing out or improving low-performing products.</li>
<li><b>Enhance Location Performance:</b> Identify locations with lower sales and analyze factors contributing to underperformance. Implement targeted strategies to boost sales in these locations.</li>
<li><b>Weekday vs. Weekend Promotions:</b> Leverage sales patterns to design promotions and marketing campaigns tailored for weekdays and weekends.</li>
<li><b>Time-Based Marketing:</b> Utilize insights from daily and hourly sales analysis to optimize opening hours and schedule targeted promotions.</li>
<li><b>Customer Preferences:</b> Use product sales data to understand customer preferences and tailor offerings accordingly.</li>

## Conclusion
The Coffee Shop Sales Analysis dashboard provides valuable insights into the sales performance of the coffee shop. By understanding key metrics and trends, the company can make data-driven decisions to enhance sales strategies, improve product offerings, and optimize overall performance.



