# Unified Mentor Project 2 Sales budget analysis
This repository contains all the data and information about the 2 projects that I completed as an intern in Unified Mentor from 10-05-2024 to 10-06-2024.

# About the Internship:
* Organization: Unified Mentor
* Role: Data Analyst Intern
* Timeline: 10-05-2024 to 10-06-2024
* Number of Projects: 2
* Project Names: Financial Analytics & Budget Sales Analytics

# About the Project:

## Project Name: 
 - Budget Sales Analytics
   
## Introduction:

The **AdventureWorks** is a fictitious, multinational manufacturing company. The **AdventureWorks database** covers various business aspects, including sales, production, and human resources. 

In this project I'll perform the following tasks -

1. Gather and clean data from multiple sources, including sales transactions, customer interactions, and product records.
2. Explore and analyze sales data of AdventureWorks Products from 2014 to 2016 to gain insights into the company's revenue trends and customer preferences.
3. Compare the budgeted monthly sales and actual monthly sales in 2016.
4. Categorize customers based on their buying behavior and analyze how different segments contribute to the company's revenue.
5. Identify the top-selling products in terms of revenue and quantity.
6. Develope predictive models to optimize pricing strategies, identify customer segments, and personalize marketing campaigns.
8. Communicate findings and recommendations to stakeholders in a clear and concise manner.
9. Provide actionable insights and recommendations to senior management to support strategic decision-making.


## Domain:
  - Retail & Sales

## Difficulty Level:
 - Advanced

## Problem Statement:

- Extract various information such as Sales, budget, and variance.
- You can even compare sales and budgets with various attributes.
- Extract necessary information about Products and Customers.
- Make the necessary dashboard with the best you can extract from the data.
- Use various visualization and features and make the best dashboard.
- Find key metrics and factors and show the meaningful relationships between attributes.
 
## Tools used:
  - Microsoft Excel - For Data Cleaning
  - Microsoft SQL Server - Data Preparation, Joining multiple tables, Analysis
  - Alteryx - For Data Preparation and Analysis
  - Power BI - Data Visualization & Dashboard
  - Canva - Project Report

## Methodologies used:
  - Data Profiling
  - Data Cleaning
  - Data Wrangling
  - Exploratory Data Analysis
  - Customer Segmentation
  - Data Visualization
  - Documentation

## Data Description:

There are total 5 tables in the AdventureWorks database Excel file and a separate excel file for the Budget data.

1. **Calender Sheet** -

| Column name | Datatype | Description |
| :--- | :--- | :--- |
| Date	| Date | Date | 
| DateKey	| Str | Primary Key for the Calender database | 
| Year	| Str | Year |  
| Quarter	| Str | Quarter |  
| MonthNum	| Int | Month Number | 
| Month	| Str | Month |  
| FiscalYear	| Str | Fiscal Year | 
| FiscalQuarter	| Str | Fiscal Quarter |  
| FiscalMonthNum	| Int | Fiscal Month Number | 
| FiscalMonth	| Str | Fiscal Month |  
| MonthYear	| Str | Month Year |  
| MonthYearLong | Str | Month and Year |  
| MonthYearNum	| Str | Month and Year Number |  
| WeekdayNum	| Int | Weekday Number |
| Weekday	| Str | Weekday |  
| WeekdayWeekend | Str | Whether it's Weekday or Weekend |  


2. **Customers Sheet** -

| Column name | Datatype | Description |
| :--- | :--- | :--- |
| CustomerKey	| Int | Primary key for customer dataset |
| FirstName	| Str | Firstname of the customer | 
| LastName	| Str | Lastname of the customer |
| FullName	| Str | Fullname of the customer | 
| BirthDate	| Date | Birthdate of the customer | 
| MaritalStatus	| Str | M- Married / S - Single | 
| Gender	| Str | M – Male / F – Female | 
| YearlyIncome	| Double | Yearly income |
| TotalChildren	|  Int | Total number of children |
| NumberChildrenAtHome	|  Int | Number of children staying along with their parents |
| Education	| Str | Education qualification | 
| Occupation	| Str | Present occupation | 
| HouseOwnerFlag	| Bool | 1 - Owns house / 0 - Doesn’t have a permanent address |
| NumberCarsOwned	|  Int |  Number of cars owned by the customer |
| AddressLine1	| Str | Street Address of the customer | 
| DateFirstPurchase	| Date | First date of order by the customer |
| CommuteDistance | Str | Commute Distance |

3. **Product Sheet** - 

| Column name | Datatype | Description |
| :--- | :--- | :--- |
| ProductKey	| Int | Primary Key for the product dataset |
| ProductName	| Str | Product name |
| SubCategory	| Str | Sub category name of the product |
| Category	| Str | Category name of the product |
| StandardCost	| Double | Standard cost of the product |
| Color	| Str | Color of the product |
| ListPrice	| Double | Sale price of the product |
| DaysToManufacture	| Int | Days to manufacture the product after receiving the order |
| ProductLine	| Str | Product line name | 
| ModelName	| Str |  Model name of the product |
| Photo	| Str | Imagelink of the product |
| ProductDescription	| Str | Descriptive details about the product |
| StartDate | Date | Date the product was available for sale |

4. **Territory** -

| Column name | Datatype | Description |
| :--- | :--- | :--- |
| SalesTerritoryKey	| Int | Primary Key of the Territory dataset |
| Region	| Str |  Region name of the order |
| Country	| Str | Country name of the order |
| Group	| Str | Continental region |
| RegionImage | Str | Imagelink of the region |

5. **Sales** -

| Column name | Datatype | Description |
| :--- | :--- | :--- |
| ProductKey | Int | Primary Key for the product dataset |
| OrderDate | Date | Date of the order received |
| ShipDate | Date | Date when the order left the factory for export |
| CustomerKey | Int | Primary key for customer dataset |
| PromotionKey | Int | Unique Promotion Key |
| SalesTerritoryKey | Int | Primary Key of the Territory dataset |
| SalesOrderNumber | Str | Invoice number of the order |
| SalesOrderLineNumber | Int | Quarterly Sales for each company in Crores |
| OrderQuantity | Int | Number of quantities ordered for a product |
| UnitPrice | Double | Per unit sale price of the product |
| TotalProductCost |  Double | Cost of the product |
| SalesAmount | Double | Total sales price of the product |
| TaxAmt | Double | Tax collected for the product sold |

6. **Budget** -

| Column name | Datatype | Description |
| :--- | :--- | :--- |
| Category| Str | Category of the product |
| Subcategory	| Str | Subcategory of the product | 
| ProductName	| Str | Name of the product | 
| Jan, 2016	| Double | Budget in January 2016 (in Dollar) |
| Feb, 2016 | Double | Budget in February 2016 (in Dollar) | 
| Mar, 2016	| Double | Budget in March 2016 (in Dollar) | 
| Apr, 2016 | Double | Budget in April 2016 (in Dollar) | 
| May, 2016	| Double | Budget in May 2016 (in Dollar) |
| Jun, 2016	| Double | Budget in June 2016 (in Dollar) | 
| Jul, 2016 | Double | Budget in July 2016 (in Dollar) | 
| Aug, 2016	| Double | Budget in August 2016 (in Dollar) | 
| Sep, 2016 | Double | Budget in September 2016 (in Dollar) | 
| Oct, 2016	| Double | Budget in October 2016 (in Dollar) | 
| Nov, 2016	| Double | Budget in November 2016 (in Dollar) | 
| Dec, 2016 | Double | Budget in December 2016 (in Dollar) | 

## Metrics used:
Metrics will help us measure and evaluate the sales performance, and that can provide quantitative and qualitative information about the sales data. Some of the important metrics to use for our exploratory data analysis are -

1. **Sales Revenue**: Total revenue generated from sales over a specific period.
2. **Sales Quantity**: Total number of units or products sold.
3. **Average Order Value (AOV)**: Average revenue earned per order.
4. **Customer Acquisition Cost (CAC)**: Cost incurred to acquire a new customer.
5. **Customer Lifetime Value (CLV)**: Predicted revenue that a customer will generate over their lifetime.
6. **Sales Growth Rate**: Percentage increase or decrease in sales over a defined period.
7. **Customer Retention Rate**: Percentage of customers retained over a period.
8. **Sales by Product Category**: Revenue or quantity of sales for each product category.
9. **Sales by Customer Segment**: Revenue or quantity of sales by different customer segments (e.g., new customers vs. returning customers).
10. **Sales by Territory**: Revenue or quantity of sales by geographical territory.
11. **Sales by Time Period (Calendar)**: Revenue or quantity of sales analyzed over different time periods (daily, weekly, monthly, quarterly, annually).
12. **Product Performance**: Analysis of how well each product is selling (e.g., top-selling products, slow-moving products).
13. **Customer Churn Rate**: Percentage of customers who stopped buying your product or service.

## Data Cleaning:

I used Microsoft Excel for cleaning the datasets. In this phase I checked for duplicate entries, corrected typographical errors, joined column from external dataset, removed redundant columns, organized the data by sorting and filtering. 
In addition to the existing tables, I have also used an updated [AdventureWorks sample databases](https://github.com/Microsoft/sql-server-samples/releases/tag/adventureworks) for imputing missing values in the existing tables. For this task I used Microsoft SQL Server for querying the relevant data.

I've documented all the changes made in the datasets in this [Changelog](https://docs.google.com/document/d/1Lkti0vkrVCjyIRbY__gWmLg4-YVXavDR0ro0j2RtG0Q/edit?usp=sharing).

## Data Transformation:

After cleaning and removing the redundant columns, I loaded the datasets into Alteryx to perform Data Transformation. Here I created new columns (both numeric and categorical), joined the datasets to create more comprehensive dataset that will simplify our analysis process. In the end, we end up with these 5 tables - 

1. Customer_Demographic_Data
2. Customer_Order_Details
3. Sales_Data
4. Product_Details_Data
5. Seasonal_Calender_Data

This is how the Entity Relationship Diagram (ERD) looks like for this database after transformation - 







## Data Exploration: 

## Data Analysis:

### Seasonal patterns:

* How has the **sales revenue trended over time**?
* Do sales exhibit **seasonal trends**? For example, are there spikes during holidays or specific months?
   
### Products:

* Which products are the **best sellers** and **worst sellers** in terms of **revenue**?
* Are there any products that consistently **underperform** in terms of quantity and revenue?

### Companies:

* What are the top 10 companies in terms of overall **revenue**?
* What are the least 10 companies in terms of overall **revenue**?

### Regions:

* Which **regions** exhibit the highest and lowest sales performance?
* Are there any **regional variations** in demand or customer preferences?
* Which **states** exhibit the highest and lowest sales performance?
* Which cities exhibit the highest and lowest sales performance?

### Correlations and causality:
* Are there any **correlations** between regional factors (e.g., population density, economic indicators) and sales performance?



## Interpretation of Results:
## Reporting: 
## Recommendations:

## Conclusions:
## Limitations of the project:
## Future Ideas:

## References:

* [AdventureWorks sample databases](https://github.com/Microsoft/sql-server-samples/releases/tag/adventureworks)
* [How to Download and Install AdventureWorks Database in SQL?](https://www.geeksforgeeks.org/how-to-download-and-install-adventureworks-database-in-sql/)
* [What Is Average Order Value (AOV)? Definition and How to Calculate](https://amplitude.com/blog/what-is-average-order-value-aov)
