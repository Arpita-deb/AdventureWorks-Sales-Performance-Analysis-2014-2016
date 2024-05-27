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

After cleaning and removing the redundant columns, I loaded the datasets into Alteryx to perform Data Transformation. Here I created new columns (both numeric and categorical), joined the datasets to create more comprehensive dataset that will simplify our analysis process. In the end, we end up with these 6 tables - 

1. Customer_Demographic_Data - 17 columns and 17918 rows
2. Customer_Order_Details - 5 columns and 6619 rows
3. Sales_Data - 18 columns and 58189 rows
4. Product_Details_Data - 16 columns and 406 rows
5. Calender_Data - 7 columns and ___ rows
6. Territory_Data - 5 columns and 10 rows

This is how the Entity Relationship Diagram (ERD) looks like for this database after transformation - 


## Data Exploration: 

1. **Sales Trends and Patterns:**
   - What are the overall sales trends from 2014 to 2016?
   - Are there any seasonal patterns or fluctuations in sales?
   - How do different product categories perform over time?
   - What is the total revenue generated and quantity sold from sales over the years?
   - What is the total monthly revenue generated  and quantity sold from sales over the years?
   - What is the total quarterly generated and quantity sold  from sales over the years?
   - What is the total weekly generated and quantity sold  from sales over the years?
   - What is the sales growth rate over the years?
   - What is the average order value per order?

2. **Budget vs. Actual Analysis:**
   - How does actual sales data from 2016 compare to the budgeted sales figures?
   - Are there any significant deviations, and if so, what are the reasons behind them?
   - Which products or territories contributed the most to any variance?

3. **Customer Segmentation and Demographics:**
   - What are the demographic profiles of our customers (age, gender, location)?
   - Do certain demographics correlate with higher sales or specific product preferences?
   - How can customer demographics inform targeted marketing or product strategies?
   - Which types of accounts are most likely to expand?
   - Which accounts are most likely to churn?
   - How does customer demographics impact sales?
   - What is the customer acquisition cost?
   - What is the customer lifetime value and customer churn rate?
   - What is the customer retention rate over the years?
   - What are the sales generated by different customer segments?

4. **Product Performance and Analysis:**
   - Which products are top sellers overall and within specific time periods?
   - Are there products that are consistently underperforming or experiencing declining sales?
   - What is the relationship between product features (size, color, price range) and sales performance?
   
5. **Territory and Regional Analysis:**
   - How do sales vary across different territories or regions?
   - Are there geographical patterns in sales performance?
   - Which territories show the highest growth potential or need additional focus?

6. **Order Details and Customer Behavior:**
   - What are the average order sizes and frequencies?
   - Are there any trends in customer purchasing behavior (e.g., repeat purchases, cross-selling opportunities)?
   - How do promotions or discounts impact order volumes?

9. **Forecasting and Predictive Analysis:**
   - Can historical sales data be used to forecast future sales trends?
   - What factors (economic, seasonal, promotional) influence sales forecasts the most?
   - How accurate are our sales predictions compared to actual outcomes?

## Data Analysis:

## RFM(Recency, Frequency, Monetary) Analysis for Customer Segmentation:
Recency, frequency, monetary value (RFM) is a model used in marketing analysis that segments a company’s customer base by their purchasing patterns or habits. We evaluate these metrics by asking these questions -
* Recency: When was the last sales transaction with this customer?
* Frequency: How often do we sell to this customer?
* Monetary: How much did we sell to this customer across its entire lifetime?

We'll then give each customer a RFM score from 1-5 with 1 being not good and 5 excellent. 

### Recency: (2, 366)

   - 5: R< 75
   - 4: R>= 75 and R <148
   - 3: R>= 148 and R <221
   - 2: R>=221 and R <294
   - 1: R>=294

### Frequency: (2, 26)

   - 1: F<7
   - 2: F>= 7 and F<12
   - 3: F>=12 and F< 17
   - 4: F>=17 and F< 22
   - 5: F>= 22

### Monetary: (15.0984, 14359.0104)

   - 1: M< 2883.8808
   - 2: M>=2883.8808 and M< 5752.6632
   - 3: M>=5752.6632 and M< 8621.4456
   - 4: M>= 8621.4456 and M< 11490.228
   - 5: M>=11490.228

Segmenting customers based on RFM (Recency, Frequency, Monetary) scores into 5-6 segments allows you to effectively target different groups with tailored marketing strategies and customer experiences. Here are some criteria and characteristics you can consider for each segment:

### Criteria for 5-6 Segments Based on RFM Scores:

1. **Champions:**
   - **RFM Score:** 555
   - **Characteristics:**
     - High Recency: Recently made purchases.
     - High Frequency: Regularly purchases.
     - High Monetary Value: Spends significantly per transaction.
   - **Behavior:** Loyal customers who are likely to make frequent high-value purchases. Target with exclusive offers and rewards to maintain loyalty.

2. **Potential Loyalists:**
   - **RFM Score:**  544 or 545 or 554
   - **Characteristics:**
     - High Recency: Recently made purchases.
     - Moderate to High Frequency: Regularly purchases but not as frequently as Champions.
     - Moderate to High Monetary Value: Spends decently per transaction.
   - **Behavior:** Likely to become Champions with targeted incentives and personalized recommendations. Nurture with loyalty programs and personalized communications.

3. **Recent Customers:**
   - **RFM Score:** 534, 543, 533
   - **Characteristics:**
     - High Recency: Recently made purchases.
     - Low to Moderate Frequency: Makes purchases occasionally.
     - Moderate Monetary Value: Spends moderately per transaction.
   - **Behavior:** Recent buyers who may need encouragement to increase frequency. Focus on engagement strategies and product education to drive repeat purchases.

4. **Promising New Customers:**
   - **RFM Score:** 422, 322, 333,323, 433, 423
   - **Characteristics:**
     - Moderate Recency: Made purchases somewhat recently.
     - Low Frequency: Rarely purchases.
     - Low Monetary Value: Spends minimally per transaction.
   - **Behavior:** New customers who need nurturing to increase engagement and loyalty. Offer welcome discounts, personalized recommendations, and educational content to encourage repeat purchases.

5. **Needs Attention:**
   - **RFM Score:** 222, 221, 212
   - **Characteristics:**
     - Low Recency: Hasn't made purchases recently.
     - Low Frequency: Rarely purchases.
     - Low Monetary Value: Spends minimally per transaction.
   - **Behavior:** At risk of churn. Re-engage with targeted reactivation campaigns, special offers, and personalized win-back strategies to regain their interest.

6. **At Risk/Churned Customers:**
   - **RFM Score:** 111
   - **Characteristics:**
     - Very Low Recency: Hasn't purchased in a long time.
     - Very Low Frequency: Rarely or never purchases.
     - Very Low Monetary Value: Rarely spends or spent minimally.
   - **Behavior:** High risk of churn or already churned. Implement aggressive win-back strategies, personalized reactivation offers, and customer feedback surveys to understand reasons for churn.



### Products Analysis:

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
* [What Is Recency, Frequency, Monetary Value (RFM) in Marketing?](https://www.investopedia.com/terms/r/rfm-recency-frequency-monetary-value.asp)
* [RFM analysis for Customer Segmentation](https://clevertap.com/blog/rfm-analysis/#How_to_Implement_RFM_Analysis_Used_in_Customer_Segmentation)
