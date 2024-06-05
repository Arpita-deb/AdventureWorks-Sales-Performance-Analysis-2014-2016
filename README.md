# AdventureWorks Sales Budget Analysis
## Unified Mentor Internship Project 2: Sales Budget Analytics

![AdventureWorks Sales Budget Analysis](https://github.com/Arpita-deb/Top_Indian_Firms_Market_Capitalization-Analysis_For_2018/assets/139372731/9f129258-bad5-464f-add0-9fd4ae20bf8f)

# About the Internship:

* Organization: Unified Mentor
* Role: Data Analyst Intern
* Timeline: 10-05-2024 to 10-06-2024
* Number of Projects: 2
* Project Names: Financial Analytics & Budget Sales Analytics

# About the Project:

## Project Name: 
 - Budget Sales Analysis
   
## Introduction:

The **AdventureWorks** is a fictitious, multinational manufacturing company. The **AdventureWorks database** covers various business aspects, including sales, production, and human resources. 

In this project I'll perform the following tasks -

1. Gather and clean data from multiple sources, including sales transactions, customer interactions, and product records.
2. Explore and analyze sales data of AdventureWorks Products from 2014 to 2016 to gain insights into the company's revenue trends and customer preferences.
3. Compare the budgeted monthly sales and actual monthly sales in 2016 for some products.
4. Categorize the customers based on their buying habit and analyze how different segments contribute to the company's revenue.
5. Identify the top-selling products in terms of revenue and quantity.
6. Communicate findings and recommendations to stakeholders in a clear and concise manner.
7. Provide actionable insights and recommendations to senior management to support strategic decision-making.

The Project Report is available here [AdventureWorks Sales Budget Analysis Report Presentation PDF](https://github.com/user-attachments/files/15572722/AdventureWorks.Sales.Budget.Analysis.Report.Presentation.pdf).


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
  - Microsoft SQL Server - To look up and impute values in the original datasets
  - Alteryx - For Data Preparation & Analysis
  - Power BI - Data Visualization & Dashboard
  - Canva - Project Report

## Methodologies used:
  - Data Profiling
  - Data Cleaning
  - Data Wrangling
  - Exploratory Data Analysis (EDA)
  - Customer Segmentation and RFM Analysis
  - Data Visualization
  - Documentation

## Data Description:

There are total 5 tables in the AdventureWorks database Excel file and a separate Excel file for the 2016 Budget data.

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
| SalesOrderLineNumber | Int | Number of Sales Order Line |
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
6. **Sales by Customer Segment**: Revenue or quantity of sales by different customer segments.
7. **Sales by Product Category**: Revenue or quantity of sales for each product category.
8. **Sales by Territory**: Revenue or quantity of sales by geographical territory.
9. **Sales by Time Period (Calendar)**: Revenue or quantity of sales analyzed over different time periods (monthly, quarterly, annually).
10. **Product Performance**: Analysis of how well each product is selling (e.g., top-selling products, slow-moving products).
    
## Data Cleaning:

I used Microsoft Excel for cleaning the datasets. In this phase I checked for duplicate entries, corrected typographical errors, joined columns from external dataset, removed redundant columns, organized the data by sorting and filtering. 
In addition to the existing tables, I have also used an updated [AdventureWorks sample databases](https://github.com/Microsoft/sql-server-samples/releases/tag/adventureworks) for imputing missing values in the existing tables. For this task I used Microsoft SQL Server for querying the relevant data.

## Data Transformation:

After cleaning and removing the redundant columns, I loaded the datasets into Alteryx to perform Data Transformation. Here I created new columns (both numeric and categorical), joined the datasets to create more comprehensive dataset to simplify our analysis process. In the end, I had 7 transformed tables - 

1. Customer_Demographic_Data - 17 columns and 17918 rows
2. Customer_Order_Details - 5 columns and 6619 rows
3. Sales_Data - 18 columns and 58189 rows
4. Product_Details_Data - 16 columns and 406 rows
5. Calender_Data - 6 columns and 2196 rows
6. Territory_Data - 5 columns and 10 rows
7. 2016_Budget_Data - 16 columns and 17 rows

I've documented all the changes I made to these datasets in data cleaning and transformation phase in this [Changelog](https://docs.google.com/document/d/1Lkti0vkrVCjyIRbY__gWmLg4-YVXavDR0ro0j2RtG0Q/edit?usp=sharing).

This is how the Entity Relationship Diagram (ERD) looks like for this database after transformation - 

![ERD](https://github.com/Arpita-deb/Salifort_motors_HR_analytics/assets/139372731/e5bf9985-bf5d-4b7d-92f8-812f5a554498)

## Data Exploration: 

### 1. **Sales Trends and Patterns Analysis:**
 
 The sales data contain information about sales orders from 2014 to 2017. For this analysis I've chosen 3 years from 2014 - 2016 so that I can later compare the actual sales revenue and the budget for 2016 for some products. 
   
- **What are the overall sales trends from 2014 to 2016?**

  ![1 1](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/76d09cb2-6258-4b9d-aa8c-56f27358e2ba)

- **Are there any seasonal patterns or fluctuations in sales?**
 
In the first glance we notice that 2016 has a much higher sales revenue compared to 2014 and 2015. This is reflected again in all the consequetive charts (drilled down to quarter and months) below. There's a gradual growth apparent for 2016, but a decline in 2015 after February compared to 2014. Also there is a significant spike in June for each year, which could be linked to summer season promotions or events.

After June sales drop down in July and sees little or no increase in revenue until the end of the year, except for 2016. The end-of-year months, November and December, see an increase in revenue, likely due to holiday shopping and year-end sales events.
   
- **What is the total revenue generated and quantity sold from sales over the years?**
  
 ![sales growth rate](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/32a05292-a8ff-4ae2-8af1-e0d5ca7444b9)

- **What is the total monthly revenue generated and quantity sold from sales over the years?**

 ![monthly sales and quatity](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/76331e0d-6136-4bf2-af6f-227a15919996)
 
- **What is the total quarterly generated and quantity sold from sales over the years?**

 ![1 3](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/0791f657-8dc9-4406-8a75-3a1e45e651d5)

- **What is the number of orders placed per year?**

 ![1 5](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/da7520c6-0ee4-4dc6-b312-9944d95b77f6)
   
- **What is the monthly number of customers per year?**

![monthly num of customers](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/8a31d3cf-36c1-4df9-b5d1-a6d96cdf746e)

- **What is the Average Order Value per order, Average Order Frequency and Average Order Size?**

The Average Order Value per order is the average amount a customer spends per order.
Average Order Frequency is how often a customer makes a purchase. 
Average Order Size is the average quantity of products bought per order.

 ![average order frequency](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/7f261478-ef90-4515-ac3b-b09000fe564b)

From the above table, we can say that a customer orders on average once, makes one order and spends on average $504.

### 2. **Budget vs. Actual Analysis:**

 To compare the budget for 2016 with the actual sales revenue, I used Total sales amount including tax for 13 products and calculated their sales per month in 2016. Then I joined this data with the Budget data, and calculated the variance. Variance is the difference between Actual revenue and the budget. The products with negative variance shows that for these products the budget has been overestimated.

- **How does actual sales data from 2016 compare to the budgeted sales figures?**

![Budget](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/4899f741-a5ed-4ec8-b599-8d0008156b9c)

- **Are there any significant deviations, and if so, what are the reasons behind them?**

 Out of 13 products 7 showed a negative variance. 

- **Which products or territories contributed the most to any variance?**

 Touring 2000 Blue 60 showed a significant amount of variance throughout the year especially in November where the difference between actual sales and budgeted sales exceeded about $500,000. When I checked for the reason behind the significant variance of this product by further drilling down the data by country and months, I found that in many countries such as in Germany, Canada, Australia and France this product has not been sold in many months. This might be a reason why the actual sales amount lagged so much behind the budgeted sales.

Moreover, a different price of products in different countries in different months might also contribute to lower sales amount compared to the budgeted sales. 

Since the budget data does not contain the number of sales per product/month/country or any other relevant data to compare it with actual sales, I could not pinpoint the exact reasons behind the variances of these products.

### 3. **Customer Segmentation and Demographics:**

 To perform customer segmentation I joined all the datasets to get a more comprehensive and detailed view of the customers' historical buying habit. I joined Sales, order details and customer demographic data to get sales detail for each customers as well as their demographics. Later I joined Territory to include the country of residence and product details as well. By joining the datasets, I lost some amount of sales data(the sales records for which there were no customer demographic data). So this is only a partial picture of the overall customer behavior. 

 There are total 36 columns and 31534 rows in this joined dataset which I used for both Customer Segmentation and RFM Analysis separately.

- **What are the demographic profiles of our customers (age, gender, location)?**

 For this analysis, I used the following demographic profiles to categorize customers into different groups based on similarity: Gender, Age Group, Income Category, Marital Status, Total Children, Number of Children At Home, Education, Occupation, House Ownership, Number of Cars Owned,	Country, Commute Distance and Customer Lifetime Duration (days).

- **What are the sales generated by different customer segments?**

  * Agegroup
  
  ![age group](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/9ae06372-bd86-47d6-88f5-49ec264d3044)
  ![age](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/fa502386-ada4-49e6-9a9c-72ac1e51fc3f)

  * Gender

  ![gender](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/448148b4-de10-49da-821c-11e18441c05b)
  ![gender](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/5e7bb18c-c9a0-4218-aeba-fbb540c3d97b)

  * Income Category
    
  ![income cat](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/d39387a4-b723-4d36-a93a-22c1c7af6abb)
  ![income](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/4f9a9231-fe02-407f-adea-198896c2d797)
  
  * Marital Status
 
  ![marital status](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/59f573de-8ce5-40ca-bf0c-594b861797a7)
  ![marital](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/71a61167-8799-41be-b7be-cedfeec5a5ab)

  * Total Children
  
  ![totchildren](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/8f7567b2-be89-4265-8952-26d21c3e5d14)
  ![child](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/40592db5-d7cf-41a3-b1ac-d5dceb8a59a0)

  * Number of Children At Home
  
   ![childrenathome](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/0db0a75a-a77c-432d-91e3-68121527bf18)
   ![childhome](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/6fadee2a-ed58-4740-b8a3-57192c848ba4)

  * Education
    
  ![edu](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/db05458d-8076-4ef4-899a-a6efe435c07a)
  ![edu](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/307bf92f-fbeb-4143-a16d-01fda7e73e21)

   * Occupation

  ![occu](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/02570fde-eeea-4b04-9475-158974078e7c)
  ![occu](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/e33494bb-6319-4307-b40e-38bb4372b2b1)
  * House Owner Flag (whether they own a house or not)
  
  ![houseowner](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/b59de5a2-20d5-457c-bb1c-8bd28f1affb5)
  ![house](https://github.com/Arpita-deb/netflix-movies-and-tv-shows/assets/139372731/199aeb4a-7f77-4ea5-b9a4-93785b68717f) 

  * Number of Cars Owned

  ![carsowned](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/b4309459-4ec1-411f-8151-80a30dc70b1f)
  ![cars](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/5ddab7e9-3c24-4fa9-9e9f-439836bd3e0b)

  * Country
  
  ![country](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/5c02b698-e4a6-4022-a360-94eabb4c4544)
  ![country](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/bba7a467-609a-4aee-af47-0e7e4149eacb)
  * Commute Distance

  ![commute](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/b3e03fc4-c5df-42d7-b7a3-2c44a08ee3b1)
  ![commute](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/cfa84a77-f558-4487-b2af-359743624a9b)

  * Customer Lifetime Duration (days)
    
  ![customertype](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/b59f9703-63ca-4564-8f0c-de76fce01c29)
  ![cld](https://github.com/Arpita-deb/netflix-movies-and-tv-shows/assets/139372731/4821ec9f-2906-498d-adb8-881bef60f675)

- **Which types of accounts are most likely to expand?**

Customers with a bachelor’s degree or higher education tend to have higher revenue. They may be more stable and likely to expand their engagement.
Professional and management roles also contribute significantly to revenue. These customers may have growth potential.
Homeowners are more likely to expand, as they generate higher revenue.
Customers with multiple cars (especially 2 cars) might be financially stable and willing to expand their relationship with the company.
Medium-value customers (based on customer lifetime duration) are likely to continue their engagement and potentially expand.
Customers from 40-60 age group, as they form the majority of the customer base are most likely to expand.

- **Which accounts are most likely to churn?**

Customers with lower education levels (partial high school degree) may be less stable and more likely to churn.
Skilled manual workers and clerical roles contribute less to revenue. They might be at risk of churning.
Non-homeowners (especially those without a house) may be less committed and more likely to churn.
Customers with longer commute distances (10+ miles) might find it less convenient to continue their engagement.
High-value customers (based on customer lifetime duration) could be at risk of churn if not properly engaged.
Customers who fall into the low-value category (CLV < 500 days), have low yearly income (<$63328) are most likely to churn as they might be more sensitive to price changes. 
Young adults (under 40 years) often have lower brand loyalty so may switch between brands more frequently.

- **Find the top 10  customers by Average Order Value for 2016?**

![top 10 customer by aov](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/4e0c013e-496a-4bd6-a650-52cec61c344d)
  
### 4. RFM(Recency, Frequency, Monetary) Analysis:

 Recency, frequency, monetary value (RFM) is a model used in marketing analysis that segments a company’s customer base by their purchasing patterns or habits. We evaluate these metrics by asking these questions -

* Recency: When was the last sales transaction with this customer? 
* Frequency: How often do we sell to this customer?
* Monetary: How much did we sell to this customer across its entire lifetime?

#### *Step 1 : Creating Recency, Frequency and TotalRevenue(Monetary) columns*

 * Recency: Using 2017-01-01 as our analysis day, I've calculated the difference between this day and the Last Order date for each customer.
 * Frequency: To calculate frequency, I grouped the data by customers and counted the distinct SalesOrderNumber.
 * TotalRevenue: Finally, to calculate monetary value, I grouped the data by customers and summarized the total transaction amount.

#### *Step 2: Creating R, F, M columns*

 Transforming these columns into R, F, M columns by giving each customer a score between 1 to 5.
* R Scoring
  - R = 1: when Recency >= 294 days [the higher the value of days since last business interaction with the customer, the least recent the customer, hence a lower score]
  - R = 2: when Recency >= 221 and <294
  - R = 3: when Recency>=148 and < 221
  - R = 4: when Recency>=75 and < 148
  - R = 5: when Recency< 75 [lower days since last business interaction, the more recent a customer is, hence a higher score]
   
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

I have used 6 segments of customers based on RFM Scores:

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

6. **At Risk/Churned Customers:**
   - **RFM Score:** between 4 and 3
   - **Characteristics:**
     - Very Low Recency: Hasn't purchased in a long time.
     - Very Low Frequency: Rarely or never purchases.
     - Very Low Monetary Value: Rarely spends or spent minimally.
   - **Behavior:** High risk of churn or already churned.

#### *Step 5: Calculations*

* **Number of customers per segment** -

![rfm segments](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/2e170b4e-360e-4ca9-ba48-83b59750de37)

As can be seen from the segments, we don't have all the 6 segments of customers in this scenario. But these existing segments can still shed some light on the present customer base.
For example, majority of the customers are Promising New Customers who make purchases less frequently and spend minimally. Yet with some targeted marketing efforts and personalized recommendations tactics the company can turn this customer base into a more loyal customer base. 

On the other hand, there are 142 customers who are at the risk of churning. So the company can should try to find the reasons behind their churning and take positive actions to reduce the number of churned customers.

* **Top 10 RFM customer** -

![top 10 rfm customer](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/97ebefdf-9096-4a5d-9f56-32e5e04cce10)

* **Bottom 10 RFM customers** -

![bottom 10 rfm customers](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/095eb646-bbc7-4f29-a0d3-533fde1844f3)

#### *Step 6: Recommendations for each segments*:
  
   * Segment 3 (**Recent Customers**) : Focus on engagement strategies and product education to drive repeat purchases.
   * Segment 4 (**Promising New Customers**) :  Offer welcome discounts, personalized recommendations, and educational content to encourage repeat purchases.
   * Segment 5 (**Needs Attention**) : Re-engage with targeted reactivation campaigns, special offers, and personalized win-back strategies to regain their interest.
   * Segment 6 (**At Risk Customers**) : Implement aggressive win-back strategies, personalized reactivation offers, and customer feedback surveys to understand reasons for churn.
   
### 5. **Product Performance and Analysis:**
  
- **Which products are top sellers overall and within specific time periods?**

 This table is showing Top 10 products by quantity.

 ![top 10 pdt by quantity](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/070a7bb9-93a8-4002-a12c-ec83e6a8ae97)

 This table is showing Top 10 products by Sales amount.

 ![top 10 pdt by sales](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/32c7ce1e-e1e0-4345-99ac-29a5d9fe0082)

- **Are there products that are consistently underperforming or experiencing declining sales?**

 This table is showing Bottom 10 products by quantity.

 ![bottom 10 pdt by quantity](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/f4a88379-cf33-4d6a-96af-5482fdf09f5d)

 This table is showing Bottom 10 products by Sales amount.

 ![bottom 10 pdt by sales](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/99bb74d6-1333-47c9-9eb8-1b27b1ff231d)
   
- **What are the top 10 most profitable and least profitable products for 2016?**

 ![top 10 pdts](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/d69e2138-5894-42c9-97ac-50ea94e2c23c)

 ![least 10 pdt](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/a02f5c41-043e-4750-a389-de269b4920f7)

- **What is the quantity of products sold by product category, subcategory, productline and color?**

 ![5 1](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/deeed3ba-cb7f-4677-8458-80fc74d8fd3f)

 ![5 2](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/b1209bef-d796-4542-aa04-70ef5d2331c0)

 ![5 3](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/ba1b5d1b-860f-4c7e-944d-4b67cb212a5a)

 ![5 4](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/5a9709a3-9c8f-415c-b101-b08222aa442b)

### 6. **Territory and Regional Analysis:**

- **How do sales vary across different territories or regions?**

 ![country by year and sales](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/66cf5d29-1728-47e7-96a9-c8c47807d41f)

- **Are there geographical patterns in sales performance?**

 ![6 1](https://github.com/Arpita-deb/Unified-Mentor-Project-2-Sales-budget-analysis/assets/139372731/0076245f-d82e-4a4e-aa15-b23140c5cb19)

- **Which territories show the highest growth potential or need additional focus?**

The United States and Australia are already producing high revenue. However, Canada and the UK are also showing growth potential in terms of quantity of product purchase.

## Summary:

* **2016** shows significantly higher sales revenue, higher number of orders placed, quantity ordered as well as number of customers compared to 2014 and 2015. **June** consistently experiences a significant spike in sales, possibly due to summer season promotions or events. After June, sales decline in July and remain relatively flat until year-end. **November and December** show increased revenue, likely due to holiday shopping and year-end sales.

* From Sales Budget Analysis, we found out that 7 out of 13 products have lower actual sales revenue in 2016 than was projected. A further exploration revealed lack of sales in various months and difference of pricings in various countries may have been potential reasons for their large variance.
   
* From analyzing various Customer demographics and product preference, we found out that -

  1. **Age Distribution**: The age group between 40 and 49 years consistently generated the highest revenue across all years. Following closely were customers aged 50-59 and 60-69. Thus, the majority of customers fall within the 40 to 60 age range, with a gradual decline in customer numbers after 60.

  2. **Gender Distribution**: Gender did not significantly impact revenue generation. Female customers contributed slightly more revenue than male customers.

  3. **Income Categories**: The largest segment consists of customers with low income (annual income less than $63,328).

  4. **Marital Status**: Married customers produced approximately 6.5% more revenue than single customers.

  5. **Revenue distribution by the number of children:**
        - Customers with no children generated 30% of the total revenue.
        - Customers with 2 children contributed 22%.
        - Customers with 1 child contributed 20%.
        - Customers with 3, 4, and 5 children produced 11%, 9%, and 5% of the total revenue, respectively.

  6. **Considering children at home:**
        - Customers without any children at home contributed about 60% of the total revenue.
        - Customers with 1, 2, 5, 4, and 3 children at home contributed 11%, 9%, 7%, 6%, and 5% of the total revenue, respectively.

  7. **Education Level and Revenue:**
        - Approximately 35% of the total revenue came from customers with a bachelor's degree.
        - Partial college graduates contributed 25%.
        - Those with a graduate degree accounted for 17%.
        - High school graduates contributed 15%.
        - Only 5% of the revenue was generated by customers with a partial high school degree.

  8. **Occupation and Revenue:**
        - Professional customers were responsible for 34% of the total revenue.
        - Management professionals contributed 20%.
        - Skilled manual workers accounted for 19%.
        - Clerical roles contributed 15%.
        - Manual laborers generated 10% of the revenue.

  9. **Homeownership and Revenue:**
        - Customers who owned a house produced approximately 58.7% more revenue than those who didn't.

  10. **Car Ownership and Revenue:**
        - About 28% of the revenue came from customers who owned 2 cars.
        - Customers with 1 car contributed 26%.
        - Those without a car also contributed 26%.
        - Customers with 3 cars generated 10% of the total revenue.
        - The smallest segment was customers with 4 cars, contributing 8%.

  11. **Geographic Segmentation:**
        - The highest revenue-producing customer segments were from Australia, the United States, the UK, and Canada.
        - Germany and France had the lowest revenue contribution.

  12. **Commute Distance and Revenue:**
        - Customers with a commute distance of 0-1 miles generated 38% of the total revenue.
        - Those with a commute distance of 5-10 miles contributed 18%.
        - Commute distances of 1-2 miles and 2-5 miles each accounted for 14%.
        - Customers with a commute distance of 10+ miles also contributed 14%.

  13. **Customer Lifetime Duration and Revenue:**
       - Based on customer lifetime duration (how long they've been doing business with the company), we segmented them into three categories: low, medium, and high.
       - The largest customer base falls into the medium category, with revenue 27.9% higher than low-value customers and 94% higher than high-value customers.

* From RFM Analysis, we found that majority of the customers are promising new customers who have somewhat recently purchased, with low frequency and monetary value. These customers have potential for repeating purchase, increase in frequency and spending amount with more engagement with the company. Some other segments include recent customers, at risk of churning and customers who need attention before they churn.

* From analyzing 406 products, we found that Components category has the highest number of products compared to bikes, accessories, clothing etc. Road frames, Road bikes and Mountain frames are the top product subcategory. Most of the products are in Black color and least in Grey and white.

## Power BI Dashboard:

![1](https://github.com/Arpita-deb/netflix-movies-and-tv-shows/assets/139372731/a0612b55-f521-454d-bb6a-d9e86d211ae4)

![2](https://github.com/Arpita-deb/netflix-movies-and-tv-shows/assets/139372731/cbd0b7b6-a77a-4c1a-8151-d8cb38ddb7d1)

![3](https://github.com/Arpita-deb/netflix-movies-and-tv-shows/assets/139372731/b6bcb393-fcdf-48e2-bc55-4d07312ab5e7)

## Recommendations:

1. **Targeted Marketing**: Focus marketing efforts on the 40-60 age group, as they form the majority of the customer base. Tailor marketing messages to address the needs and preferences of customers in this age range.

2. **Target High-Potential Segments:** Focus on customers with bachelor’s degrees or higher education. They consistently generate higher revenue. Tailor marketing efforts to engage and retain this segment. Prioritize professional and management roles. These customers contribute significantly to revenue. Consider personalized offers or loyalty programs for them.

3. **Retention Strategies:** Implement retention strategies for skilled manual workers and clerical roles. These segments contribute less to revenue and may be at risk of churning. Engage with homeowners proactively. They generate higher revenue and are more likely to stay loyal. Address the needs of high-value customers (based on customer lifetime duration). Keep them engaged to prevent churn.

5. **Marital Status Considerations**: Married customers may have different needs than single customers. Customize marketing messages accordingly.

4. **Child-Friendly Products**: Since 30% of customers have no children and 60% of customers have no children at home, consider offering family-friendly products.

6. **Localized Marketing**: Concentrate efforts in countries with the highest customer concentration (Australia, the United States, Canada, and the UK). Tailor marketing messages to each country's cultural nuances. Investigate reasons behind lower revenue in Germany and France. Tailor marketing strategies accordingly.

7. **Customer Retention Strategies**: Since 62% of customers fall into the low-value category (CLV < 500 days), focus on retaining them. Implement loyalty programs, personalized offers, and excellent customer service.

8. **Income-Sensitive Pricing**: Adjust pricing strategies based on income levels. Offer budget-friendly options for low-income customers and premium products for high-income customers.

## Conclusions:

In this project, I analyzed AdventureWorks Retail Company's daily sales data from 2014 to 2016 across 7 countries. After cleaning the data in Excel, I transformed it using Alteryx tools for better comprehension. Exploratory data analysis revealed customer demographics and purchasing behavior. I conducted RFM analysis, segmenting customers based on recency, frequency, and monetary metrics. Recommendations were provided for each segment. Additionally, I analyzed top and bottom performing products by revenue, quantity, and profit, visualizing the insights using Power BI.

## Limitations of the project:

* Since the Budget data only contains monthly sales budget for a few products, a detailed Budget Analysis was not possible.
* Due to joining of multiple datasets, I lost some amount of data points, which could have enriched the analysis.
* A detailed Customer Segmentation has not been performed using Cluster Analysis or other Machine Learning Techniques due to time constraint.
* The data is outdated.

## Future Ideas:

* **Budget Analysis Enhancement:** Collect more detailed budget data, including product-level budgets if possible. This will allow for a deeper understanding of budget allocation and performance. Explore seasonality in budget allocation and its impact on sales. 

* **Advanced Customer Segmentation:** Perform cluster analysis using machine learning techniques (e.g., k-means clustering, hierarchical clustering) to create more refined customer segments. Incorporate additional features beyond RFM (Recency, Frequency, Monetary) for a comprehensive segmentation (e.g., customer behavior, demographics, interactions).

* **Time-Series Forecasting:** Given the outdated data, explore time-series forecasting models to predict future sales trends. Use historical data to project sales and identify potential growth areas or challenges.

* **Customer Lifetime Value (CLV) Modeling:** Estimate CLV for different customer segments. Understand which segments contribute the most to long-term revenue. Develop strategies to retain high CLV customers and improve engagement with low CLV segments.

## References:

* [AdventureWorks sample databases](https://github.com/Microsoft/sql-server-samples/releases/tag/adventureworks)
* [How to Download and Install AdventureWorks Database in SQL?](https://www.geeksforgeeks.org/how-to-download-and-install-adventureworks-database-in-sql/)
* [What Is Average Order Value (AOV)? Definition and How to Calculate](https://amplitude.com/blog/what-is-average-order-value-aov)
* [What Is Recency, Frequency, Monetary Value (RFM) in Marketing?](https://www.investopedia.com/terms/r/rfm-recency-frequency-monetary-value.asp)
* [RFM analysis for Customer Segmentation](https://clevertap.com/blog/rfm-analysis/#How_to_Implement_RFM_Analysis_Used_in_Customer_Segmentation)
