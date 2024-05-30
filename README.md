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
6. Communicate findings and recommendations to stakeholders in a clear and concise manner.
7. Provide actionable insights and recommendations to senior management to support strategic decision-making.


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
4. **Customer Lifetime Duration**: How long ago customer last interacted with the business.
5. **Sales Growth Rate**: Percentage increase or decrease in sales over a defined period.
6. **Sales by Customer Segment**: Revenue or quantity of sales by different customer segments (e.g., new customers vs. returning customers).
7. **Sales by Product Category**: Revenue or quantity of sales for each product category.
8. **Sales by Territory**: Revenue or quantity of sales by geographical territory.
9. **Sales by Time Period (Calendar)**: Revenue or quantity of sales analyzed over different time periods (daily, weekly, monthly, quarterly, annually).
10. **Product Performance**: Analysis of how well each product is selling (e.g., top-selling products, slow-moving products).
    
## Data Cleaning:

I used Microsoft Excel for cleaning the datasets. In this phase I checked for duplicate entries, corrected typographical errors, joined column from external dataset, removed redundant columns, organized the data by sorting and filtering. 
In addition to the existing tables, I have also used an updated [AdventureWorks sample databases](https://github.com/Microsoft/sql-server-samples/releases/tag/adventureworks) for imputing missing values in the existing tables. For this task I used Microsoft SQL Server for querying the relevant data.

## Data Transformation:

After cleaning and removing the redundant columns, I loaded the datasets into Alteryx to perform Data Transformation. Here I created new columns (both numeric and categorical), joined the datasets to create more comprehensive dataset that will simplify our analysis process. In the end, we end up with these 6 tables - 

1. Customer_Demographic_Data - 17 columns and 17918 rows
2. Customer_Order_Details - 5 columns and 6619 rows
3. Sales_Data - 18 columns and 58189 rows
4. Product_Details_Data - 16 columns and 406 rows
5. Calender_Data - 6 columns and 2196 rows
6. Territory_Data - 5 columns and 10 rows

I've documented all the changes made in data cleaning and transformation phase in the datasets in this [Changelog](https://docs.google.com/document/d/1Lkti0vkrVCjyIRbY__gWmLg4-YVXavDR0ro0j2RtG0Q/edit?usp=sharing).

This is how the Entity Relationship Diagram (ERD) looks like for this database after transformation - 



## Data Exploration: 

### 1. **Sales Trends and Patterns Analysis:**
 
 The sales data contain information about sales orders from 2014 to 2017. For this analysis I've chosed 3 years from 2014 - 2016 so that I can later compare the actual sales revenue and the budget for 2016 for some products. 
   
- What are the overall sales trends from 2014 to 2016?

  ![1 1](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/76d09cb2-6258-4b9d-aa8c-56f27358e2ba)

- Are there any seasonal patterns or fluctuations in sales?
 
In the first glance we notice that 2016 has a much higher sales revenue compared to 2014 and 2015. This is reflected again in all the consequetive charts (drilled down to quarter and months) below. There's a gradual growth apparent for 2016, but a decline in 2015 after February till June. Also there is a significant spike in June for each year, which could be linked to summer season promotions or events.

After June sales drop down in July and sees little or no increase in revenue until the end of the year, except for 2016. The end-of-year months, November and December, see an increase in revenue, likely due to holiday shopping and year-end sales events.
   
- What is the total revenue generated and quantity sold from sales over the years?

 ![sales growth rate](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/32a05292-a8ff-4ae2-8af1-e0d5ca7444b9)

- What is the total monthly revenue generated and quantity sold from sales over the years?

 ![yearly and monthly sales](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/988d4b1e-39a8-41e9-9994-76fe754f2705)

 
- What is the total quarterly generated and quantity sold from sales over the years?

 ![1 3](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/0791f657-8dc9-4406-8a75-3a1e45e651d5)

- What is the number of orders placed per year?

 ![1 5](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/da7520c6-0ee4-4dc6-b312-9944d95b77f6)
   
- What is the Average Order Value per order, Average Order Frequency and Average Order Size?

 ![average order frequency](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/7f261478-ef90-4515-ac3b-b09000fe564b)

### 2. **Budget vs. Actual Analysis:**

 To compare the budget for 2016 with the actual sales revenue, I used Total sales amount including tax for 13 products and calculated their sales per month in 2016. Then I joined this data with the Budget data, and calculated the variance. Variance is the difference between Actual revenue and the budget. The products with negative variance shows that for these products the budget has been overestimated.

- How does actual sales data from 2016 compare to the budgeted sales figures?

![Budget](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/4899f741-a5ed-4ec8-b599-8d0008156b9c)

- Are there any significant deviations, and if so, what are the reasons behind them?

 Out of 13 products 7 showed a negative variance. 

- Which products or territories contributed the most to any variance?

 Touring 2000 Blue 60 showed a significant amount of variance throughout the year especially in November where the difference between actual sales and budgeted sales exceeded about $500,000. When I checked for the reason behind the significant variance of this product by further drilling down the data by country and months, I found that in many countries such as in Germany, Canada, Australia and France this product has not been sold in many months. This might be a reason why the actual sales amount lagged so much behind the budgeted sales.

Moreover, a different price of products in different countries in different months might also contribute to lower sales amount compared to the budgeted sales. 

Since the budget data does not contain the number of sales per product/month/country or other relevant data to compare it with actual sales, I could not pinpoint the exact reasons behind the variances of these products.

### 3. **Customer Segmentation and Demographics:**

 To perform customer segmentation I joined all the datasets to get a more comprehensive and detailed view of the customers. I joined Sales, order details and customer demographic data to get sales detail for each customers as well as their demographics. Later I joined Territory to include the country of residence and product details as well. There are 36 columns and 31534 rows in total. I used this joined data for both customer segmentation and RFM Analysis separately.

- What are the demographic profiles of our customers (age, gender, location)?

 For this analysis, we used the following demographic profiles that help to categorize customers into different groups based on similarity: Gender,Agegroup, Income Category, Marital Status, Total Children, Number of Children At Home, Education, Occupation, House Owner Flag (whether they own a house or not), Number of Cars Owned,	Country, Commute Distance and Customer Lifetime Duration (days).
Apart from them, I have also segmented customers based on Product SubCategory,	Category,	Color,	ProductLine	and ModelName.

- What are the sales generated by different customer segments?

  * Agegroup
  
  ![age group](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/9ae06372-bd86-47d6-88f5-49ec264d3044)
  ![age](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/29b68e88-a1d9-4a5d-8a69-658dce110025)

  * Gender

  ![gender](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/448148b4-de10-49da-821c-11e18441c05b)
  ![gender](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/ddfebe56-cd4d-4f0b-bc09-2a75a38c16c0)

  * Income Category
    
  ![income cat](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/d39387a4-b723-4d36-a93a-22c1c7af6abb)
  ![incomecate](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/bdb70f9a-b7aa-4ea1-90e4-cf2808e46e4d)
  
  * Marital Status
 
  ![marital status](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/59f573de-8ce5-40ca-bf0c-594b861797a7)
  ![marital](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/2a600acb-deb2-45ed-99ce-518be696faaf)

  * Total Children
  
  ![totchildren](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/8f7567b2-be89-4265-8952-26d21c3e5d14)
  ![child](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/c1219e20-7d5a-4f56-9e4f-cbd350b3312c)
 
  * Number of Children At Home
  
   ![childrenathome](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/0db0a75a-a77c-432d-91e3-68121527bf18)
   ![childrenathome](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/fab5acf0-6220-4cc8-8289-79aae8c22d03)

  * Education
    
  ![edu](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/db05458d-8076-4ef4-899a-a6efe435c07a)
  ![edu](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/bc058c0c-6bda-4756-b11d-1adff188acc0)

  * Occupation

  ![occu](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/02570fde-eeea-4b04-9475-158974078e7c)
  ![occu](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/386cf616-5bbd-4cd2-a495-47cc542cb6d0)

  * House Owner Flag (whether they own a house or not)
  
  ![houseowner](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/b59de5a2-20d5-457c-bb1c-8bd28f1affb5)

  * Number of Cars Owned

  ![carsowned](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/b4309459-4ec1-411f-8151-80a30dc70b1f)
  ![cars](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/3962ccb5-95ce-4f09-8839-a115cea711c1)

  * Country
  
  ![country](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/5c02b698-e4a6-4022-a360-94eabb4c4544)
  ![country](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/68024727-adbd-4cad-b5d5-97abd90ac19d)
  
  * Commute Distance

  ![commute](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/b3e03fc4-c5df-42d7-b7a3-2c44a08ee3b1)
  ![commutedist](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/38ca7c07-6859-4b90-b947-554ba1bd0574)

  * Customer Lifetime Duration (days)
    
  ![customertype](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/b59f9703-63ca-4564-8f0c-de76fce01c29)
  ![customertype](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/1d62d9ba-b3b6-4dc3-89ce-c0e20b9d75d3)
   
  * Product Category
    
  ![category](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/7cf4ccab-46f2-415f-96bf-f558ecd05819)
  ![cat](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/b6a3d4b4-82e2-4b86-9173-9d5cf5cb40d1)

   * SubCategory

  ![subcategory](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/5b629ed5-8e23-40ed-87d8-b2706eba06c5)
  ![subcat](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/10a20cb7-138d-4efe-a34c-83b95fc6d63e)

   * ProductLine

  ![pdtline](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/f1a57a53-10c6-43b3-bf33-3ab65e69252d)
  ![pdtline](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/1bfc8dd6-433c-4d78-a746-ea1433e7e2fa)

  * ModelName

  ![model](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/f5b0075c-2f9e-45d5-90e0-68d65a4b4315)

  * ProductName
  
  ![pdt](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/51a068dc-88b7-4615-8efd-52412e4a30d2)

  * Color

  ![color](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/8e5a8c32-02a2-4ad4-9439-278be285fda5)
  ![color](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/8359e3ab-49bf-4e5a-8d97-e4265f2c9ba9)

- Do certain demographics correlate with higher sales or specific product preferences?



- How can customer demographics inform targeted marketing or product strategies?

- Which types of accounts are most likely to expand?

- Which accounts are most likely to churn?

- How does customer demographics impact sales?

- Find the top 10  customers by Average Order Value for 2016?

![top 10 customer by aov](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/4e0c013e-496a-4bd6-a650-52cec61c344d)
  
### 4. RFM(Recency, Frequency, Monetary) Analysis:

 Recency, frequency, monetary value (RFM) is a model used in marketing analysis that segments a company’s customer base by their purchasing patterns or habits. We evaluate these metrics by asking these questions -

* Recency: When was the last sales transaction with this customer? 
* Frequency: How often do we sell to this customer?
* Monetary: How much did we sell to this customer across its entire lifetime?

#### *Step 1 : Creating Recency, Frequency and TotalRevenue columns*

 Recency: Using 2017-01-01 as our analysis day, I've calculated the difference between this day and the Last Order date for each customer.
 Frequency: To calculate frequency, I grouped the data by customers and counted the distinct SalesOrderNumber to give us the variable F.
 TotalRevenue: Finally, to calculate monetary value, I grouped the data by customers and summarized the total transaction amount as the variable M.

#### *Step 2: Creating R, F, M columns*

 Transforming these columns into R, F, M columns by giving each customer a score between 1 to 5.
* R Scoring
  - R = 1: when Recency >= 294 days
  - R = 2: when Recency >= 221 and <294
  - R = 3: when Recency>=148 and < 221
  - R = 4: when Recency>=75 and < 148
  - R = 5: when Recency< 75
   
* F Scoring
  - F = 1: when Frequency < 7
  - F = 2: when Frequency >= 7 and <12
  - F = 3: when Frequency>=12 and < 17
  - F = 4: when Frequency>=17 and < 22
  - F = 5: when Frequency>= 22

* M Scoring
  - M = 1: when TotalRevenue < 2883.8808
  - M = 2: when TotalRevenue >=2883.8808 and < 5752.6632
  - M = 3: when TotalRevenue >=5752.6632 and < 8621.4456
  - M = 4: when TotalRevenue >= 8621.4456 and < 11490.228
  - M = 5: when TotalRevenue >=11490.228

#### *Step 3: RFMProfile Score*

Then I created RFMProfile which is the sum of the three variables R, F and M. 

A value of 15 (R = 5, F=5, M = 5) will give us the highly valued customers whereas a value as low as 3 (R=1, F=1, M=1) will give us the customers who have churned.

#### *Step 4: Segmenting customers based on RFM (Recency, Frequency, Monetary) scores 6 segments*

**Criteria for 5-6 Segments Based on RFM Scores:**

1. **Champions:**
   - **RFM Score:** 15
   - **Characteristics:**
     - High Recency: Recently made purchases.
     - High Frequency: Regularly purchases.
     - High Monetary Value: Spends significantly per transaction.
   - **Behavior:** Loyal customers who are likely to make frequent high-value purchases. 

2. **Potential Loyalists:**
   - **RFM Score:**  between 12 and 15
   - **Characteristics:**
     - High Recency: Recently made purchases.
     - Moderate to High Frequency: Regularly purchases but not as frequently as Champions.
     - Moderate to High Monetary Value: Spends decently per transaction.
   - **Behavior:** Likely to become Champions with targeted incentives and personalized recommendations.

3. **Recent Customers:**
   - **RFM Score:**  between 9 and 12
   - **Characteristics:**
     - High Recency: Recently made purchases.
     - Low to Moderate Frequency: Makes purchases occasionally.
     - Moderate Monetary Value: Spends moderately per transaction.
   - **Behavior:** Recent buyers who may need encouragement to increase frequency. 

4. **Promising New Customers:**
   - **RFM Score:** between 6 and 9
   - **Characteristics:**
     - Moderate Recency: Made purchases somewhat recently.
     - Low Frequency: Rarely purchases.
     - Low Monetary Value: Spends minimally per transaction.
   - **Behavior:** New customers who need nurturing to increase engagement and loyalty. 

5. **Needs Attention:**
   - **RFM Score:** between 4 and 6
   - **Characteristics:**
     - Low Recency: Hasn't made purchases recently.
     - Low Frequency: Rarely purchases.
     - Low Monetary Value: Spends minimally per transaction.
   - **Behavior:** At risk of churn. 

6. **At Risk Customers:**
   - **RFM Score:** between 4 and 2
   - **Characteristics:**
     - Very Low Recency: Hasn't purchased in a long time.
     - Very Low Frequency: Rarely or never purchases.
     - Very Low Monetary Value: Rarely spends or spent minimally.
   - **Behavior:** High risk of churn or already churned.

7. **Churned Customers**
   - **RFM Score:** less than 2
   - **Characteristics:**
     - Very Low Recency: Hasn't purchased in a long time.
     - Very Low Frequency: Rarely or never purchases.
     - Very Low Monetary Value: Rarely spends or spent minimally.
   - **Behavior:** Already churned. 

#### *Step 5: Calculations*

* **Number of customers per segment** -

![rfm segments](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/2e170b4e-360e-4ca9-ba48-83b59750de37)

As can be seen from the segments, we don't have all the 7 segments of customers in this scenario. But these existing segments can also shed light on the present customer base.

* **Top 10 RFM customer** -

![top 10 rfm customer](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/97ebefdf-9096-4a5d-9f56-32e5e04cce10)

* **Bottom 10 RFM customers** -

![bottom 10 rfm customers](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/095eb646-bbc7-4f29-a0d3-533fde1844f3)

#### *Step 6: Recommendations for each segments*:

   * Segment 5 (**Needs Attention**) : Re-engage with targeted reactivation campaigns, special offers, and personalized win-back strategies to regain their interest.
   * Segment 6 (**At Risk Customers**) : Implement aggressive win-back strategies, personalized reactivation offers, and customer feedback surveys to understand reasons for churn.
   * Segment 4 (**Promising New Customers**) :  Offer welcome discounts, personalized recommendations, and educational content to encourage repeat purchases.
   * Segment 3 (**Recent Customers**) : Focus on engagement strategies and product education to drive repeat purchases.

### 5. **Product Performance and Analysis:**
  
- Which products are top sellers overall and within specific time periods?

 This table is showing Top 10 products by quantity.

 ![top 10 pdt by quantity](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/070a7bb9-93a8-4002-a12c-ec83e6a8ae97)

 This table is showing Top 10 products by Sales amount.

 ![top 10 pdt by sales](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/32c7ce1e-e1e0-4345-99ac-29a5d9fe0082)

- Are there products that are consistently underperforming or experiencing declining sales?

 This table is showing Bottom 10 products by quantity.

 ![bottom 10 pdt by quantity](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/f4a88379-cf33-4d6a-96af-5482fdf09f5d)

 This table is showing Bottom 10 products by Sales amount.

 ![bottom 10 pdt by sales](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/99bb74d6-1333-47c9-9eb8-1b27b1ff231d)
   
- What is the quantity of products sold by product category, subcategory, productline and color?

 ![5 1](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/deeed3ba-cb7f-4677-8458-80fc74d8fd3f)

 ![5 2](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/b1209bef-d796-4542-aa04-70ef5d2331c0)

 ![5 3](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/ba1b5d1b-860f-4c7e-944d-4b67cb212a5a)

 ![5 4](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/946261eb-1c8d-46c4-a05b-939574b240c0) 

### 6. **Territory and Regional Analysis:**

- How do sales vary across different territories or regions?

 ![country by year and sales](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/66cf5d29-1728-47e7-96a9-c8c47807d41f)

- Are there geographical patterns in sales performance?

 ![6 1](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/0076245f-d82e-4a4e-aa15-b23140c5cb19)

- Which territories show the highest growth potential or need additional focus?

The United States and Australia are already producing high revenue. However, Canada and the UK also showing growth potential in terms of quantity of product purchase.

## Summary:

From Sales Trend analysis:

**2016** shows significantly higher sales revenue, higher number of orders placed, quantity ordered as well as number of customers compared to 2014 and 2015. **June** consistently experiences a significant spike in sales, possibly due to summer season promotions or events. After June, sales decline in July and remain relatively flat until year-end. **November and December** show increased revenue, likely due to holiday shopping and year-end sales.


From Customer Segmentation:

1. **Age Distribution**:
   - Majority of the customers fall within the 40 to 60 years age range, with a gradual decrease in numbers after 60.

2. **Car Ownership**:
   - Approximately 31% of customers own 2 cars, followed by 1 car (25%), no cars (24%), 3 cars (10%), and 4 cars (8%).

3. **Product Preferences**:
   - 51% of customers purchase bike accessories, 35% buy bikes, and 13% purchase clothing.

4. **Family Size**:
   - 30% of customers have no children, 20% have 2 children, and 19% have 1 child.

5. **Childless Customers**:
   - About 58% of the total customer base does not have any children at home.

6. **Color Preferences**:
   - Excluding products with unknown color details, black products are most popular, followed by red and yellow. White products are least favored.

7. **Commute Distance**:
   - 37% of customers have a commute distance of 0-1 miles, while 18% travel 5-10 miles, 15% travel 1-2 miles, 14% travel 2-5 miles, and 14% travel over 10 miles.

8. **Geographic Distribution**:
   - Most customers are from Australia, the United States, Canada, and the UK. A smaller number are from Germany and France.

9. **Customer Lifetime Value (CLV)**:
   - Segmented into three categories (low, medium, and high).
   - 62% of customers fall into the low-value category (CLV < 500 days), followed by medium-value (36%) and high-value (1.85%).

10. **Education Levels**:
    - 33% of total customers have a bachelor's degree, while only 6% have a partial high school degree.

11. **Gender Distribution**:
    - No significant difference based on gender. Female customers slightly outnumber male customers (50.19% vs. 49.81%).

12. **Income Categories**:
    - 53% of customers have low income (annual income < $63,328), 37% have medium income, and 8% have high income.

13. **Marital Status**:
    - 55% of customers are married, while 44% are single.

14. **Occupation**:
    - Most customers are professionals.

15. **Product Preferences (Specific)**:
    - Majority of customers purchase sports products, particularly sports tires and tubes, road bikes, and mountain bikes.

## Recommendations:

## Conclusions:

## Limitations of the project:

* Since the Budget data only contains monthly sales budget for a few products, a detailed Budget Analysis was not possible.
* Due to joining of multiple datasets, we lost many data points, that could have enriched our analysis.
* A detailed Customer Segmentation has not been performed using Cluster Analysis or other Machine Learning Techniques due to time constraint. 


## Future Ideas:

## References:

* [AdventureWorks sample databases](https://github.com/Microsoft/sql-server-samples/releases/tag/adventureworks)
* [How to Download and Install AdventureWorks Database in SQL?](https://www.geeksforgeeks.org/how-to-download-and-install-adventureworks-database-in-sql/)
* [What Is Average Order Value (AOV)? Definition and How to Calculate](https://amplitude.com/blog/what-is-average-order-value-aov)
* [What Is Recency, Frequency, Monetary Value (RFM) in Marketing?](https://www.investopedia.com/terms/r/rfm-recency-frequency-monetary-value.asp)
* [RFM analysis for Customer Segmentation](https://clevertap.com/blog/rfm-analysis/#How_to_Implement_RFM_Analysis_Used_in_Customer_Segmentation)
