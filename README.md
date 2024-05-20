# Unified Mentor Project 2 Sales budget analysis

# About the Internship:
This repository contains all the data and information about the 2 projects that I completed as an intern in Unified Mentor from 10-05-2024 to 10-06-2024.

* Organization: Unified Mentor
* Role: Data Analyst Intern
* Timeline: 10-05-2024 to 10-06-2024
* Number of Projects: 2
* Project Names: Financial Analytics & Budget Sales Analytics

# About the Project:

## Project Name: 
 - Budget Sales Analytics
## Introduction:

## Domain:
  - Retail & Sales

## Difficulty Level:
 - Advanced

## Problem Statement:
 - Our "Domain Sale" process is structured to help potential buyers purchase the domain they want immediately without the hassle of contacting the seller directly. A seller lists a domain for sale at a specific price in our Marketplace. An interested buyer sees this domain for sale and decides to buy it.
Extract various information such as Sales, budget, and variance. You can even compare sales and budgets with various attributes. Extract necessary information about Products and Customers. Make the necessary dashboard with the best you can extract from the data. Use various visualization and features and make the best dashboard. Find key metrics and factors and show the meaningful relationships between attributes

## Tools used:
  - Microsoft Excel - For Initial Data Cleaning (Removing Typographic error)
  - Alteryx - Data Preparation, Join, Analysis
  - Power BI - Data Visualization & Dashboard
  - Google Slides and Canva - Timeline Presentation and Project Report

## Methodologies used:

  - Data Profiling
  - Data Cleaning
  - Data Wrangling
  - Exploratory Data Analysis
  - Data Visualization
  - Documentation

## Data Description:
  
1. **[Adventure_Works_Database]()**

| Column name | Datatype | Type | Description |
| :--- | :--- | :--- | :--- |
| ProductKey | integer | NON NULLABLE| Index of the rows |
| OrderDate | string | NON NULLABLE | Name of the Companies |
| ShipDate | double | NON NULLABLE | Market Capitalization for each company in Crores |
| CustomerKey | double | NON NULLABLE | Quarterly Sales for each company in Crores |
| PromotionKey | integer | NON NULLABLE| Index of the rows |
| SalesTerritoryKey | string | NON NULLABLE | Name of the Companies |
| SalesOrderNumber | double | NON NULLABLE | Market Capitalization for each company in Crores |
| SalesOrderLineNumber | double | NON NULLABLE | Quarterly Sales for each company in Crores |
| OrderQuantity | integer | NON NULLABLE| Index of the rows |
| UnitPrice | string | NON NULLABLE | Name of the Companies |
| TotalProductCost | double | NON NULLABLE | Market Capitalization for each company in Crores |
| SalesAmount | double | NON NULLABLE | Quarterly Sales for each company in Crores |
| TaxAmt | double | NON NULLABLE | Quarterly Sales for each company in Crores |
| StandardCost | integer | NON NULLABLE| Index of the rows |
| List Price | string | NON NULLABLE | Name of the Companies |
| diif std cost | double | NON NULLABLE | Market Capitalization for each company in Crores |
| diff list price | double | NON NULLABLE | Quarterly Sales for each company in Crores |

2. **[Budget]()**
														
| Column name | Datatype | Type | Description |
| :--- | :--- | :--- | :--- |
| Category | integer | NON NULLABLE| Index of the rows |
| Subcategory | string | NON NULLABLE | Name of the Companies |
| ProductName | double | NON NULLABLE | Market Capitalization for each company in Crores |
| Jan, 2016 | double | NON NULLABLE | Quarterly Sales for each company in Crores |
| Feb, 2016	 | integer | NON NULLABLE| Index of the rows |
| Mar, 2016 | string | NON NULLABLE | Name of the Companies |
| Apr, 2016 | double | NON NULLABLE | Market Capitalization for each company in Crores |
| May, 2016 | double | NON NULLABLE | Quarterly Sales for each company in Crores |
| Jun, 2016 | integer | NON NULLABLE| Index of the rows |
| Jul, 2016 | string | NON NULLABLE | Name of the Companies |
| Aug, 2016 | double | NON NULLABLE | Market Capitalization for each company in Crores |
| Sep, 2016 | double | NON NULLABLE | Quarterly Sales for each company in Crores |
| Oct, 2016 | double | NON NULLABLE | Quarterly Sales for each company in Crores |
| Nov, 2016 | double | NON NULLABLE | Market Capitalization for each company in Crores |
| Dec, 2016 | double | NON NULLABLE | Quarterly Sales for each company in Crores |
| Grand Total | double | NON NULLABLE | Quarterly Sales for each company in Crores |

### 1. sales_orders_sheet

| Column Name | Type | Description |
| :--- | :--- | :--- |
| order_number | str | Uniquely identifies each record |
| sales_channel | str | Channel used for sales |
| warehouse_code | str | Warehouse code |
| procured_date | date | Procurement date of the order |
| order_date | date | Order date of the order |
| ship_date | date | Shipping date of the order |
| delivery_date | date | Delivery date of the order |
| currency_code | str | Currency type |
| sales_team_id | int | Sales team id |
| customer_id | int | Customer id |
| store__id | int | Store id |
| product_id | int | Product id |
| order_quantity | int | Quantity of the order |
| discount_applied | float | Percentage of discount applied |
| unit_price | float | Unit price of the order |
| unit_cost | float | Unit cost of the order |

### 2. customers_sheet
| Column Name | Type | Description |
| :--- | :--- | :--- |
| customer_id | int | Customer id |
| customer_name | str | Name of the customer |

### 3. store_locations_sheet
| Column Name | Type | Description |
| :--- | :--- | :--- |
| store__id | int | Uniquely identify each store |
| city_name | str | City of the store location |
| county | str | County of the store location |
| state_code | str | State code of the store location |
| state | str | State of the store location |
| type | str | Type of region to which the store belongs |
| latitude | float | Latitude of the individual store |
| longitude | float | Longitude of the individual store |
| location | text | Coordinates of the store location|
| area_code | int | Area code of the store |
| population | int | Location population |
| household_income | int | Household income in USD of the store location |
| median_income | int | Median income in USD of the store location |
| land_area | int | Land area of the location |
| water_area | int | Water area of the location |
| time_zone | str | Time zone of the location |

### 4. products_sheet
| Column Name | Type | Description |
| :--- | :--- | :--- |
| product_id | int | Uniquely identifies each product |
| product_name | str | Name of the product |

### 5. regions_sheet
| Column Name | Type | Description |
| :--- | :--- | :--- |
| state_code | str | Uniquely identifies each state |
| state | str | US state name |
| region | str | US region of individual state |

## Important Metrics to measure:
Metrics will help us measure and evaluate the sales performance, and that can provide quantitative and qualitative information about the sales data. Some of the important metrics to use for our exploratory data analysis are -

* Sales volume - The number of units of a product or service sold.
* Sales revenue/ Total Revenue - The total amount of money received from selling goods or services. It's calculated as `Sales Revenue = Sales Volume * Selling Price`.
* Profit per product - The difference between the selling price and the cost of a product. It's calculated as `Profit per Product = Selling Price - Cost of Goods Sold`.
* Total sales per year/quarter/month - The total sales volume or revenue during a specific time period.
* Total sales per region/state/county/product/channel/teams - The total sales volume or revenue for a specific category.
* Year-Over-Year Growth - The percentage change in a variable over a year. It's calculated as `Year-Over-Year Growth = (Current Year Value - Last Year Value) / Last Year Value * 100%`.
* Sales growth rate - The percentage increase in sales over a specific period. It's calculated as `Sales Growth Rate = (Current Period Sales - Previous Period Sales) / Previous Period Sales * 100%`.
* Sales mix - The proportion of each product sold relative to total sales.
* Sales trends - Patterns or tendencies in sales over a period of time.
* Average order value - The average amount spent each time a customer places an order. It's calculated as `Average Order Value = Total Revenue / Number of Orders`.
* Sales variance - The difference between actual sales and forecasted sales.
* Sales forecast accuracy - The closeness of the forecasted sales to the actual sales. It's calculated as `Sales Forecast Accuracy = 1 - (Absolute Error / Actual Sales)`.

## Data Cleaning:
## Data Exploration: 
## Data Analysis:

### Seasonal patterns:

* How has the **sales revenue trended over time**?
* Do sales exhibit **seasonal trends**? For example, are there spikes during holidays or specific months?
 
From this line chart we can notice some seasonalities among 3 years.

* **2018**: Revenue escalates from May through August, then diminishes in October. A resurgence in revenue occurs from October to December.

* **2019**: A decline in revenue is observed from January to February, stabilizing in March. A rise in April is followed by a gradual decrease until July. Revenue ascends again in August, falls in September and October, and climbs in November, only to fall once more as December concludes the year.

* **2020**: Revenue consistently falls from January to March, then recovers until May. A drop is seen in June, with July marking the peak revenue for 2020, which then declines around September. A slight increase in October is followed by a stable revenue pattern for the remainder of the year.

Regarding seasonal patterns, it appears that:

- The mid-year months, particularly **May to August**, are generally associated with higher revenue, which could be linked to summer season promotions or events.
- There's a noticeable dip in **October** across all three years, suggesting a potential seasonal downturn during this period.
- The end-of-year months, **November and December**, often show an increase in revenue, likely due to holiday shopping and year-end sales events.
   
### Products:

* Which products are the **best sellers** and **worst sellers** in terms of **revenue**?

   It appears that Accessories, Rugs, and Platters have generated the highest total revenue, while Bedroom Furniture, Bean Bags, and Pillows have generated the lowest total revenue.

   If we look closer at the change in revenue over the years, we can identify 23 products that generated high revenue in 2020 compared to previous years. These are Accessories, Bakeware, Bar Tools, Basketball, Bean Bags, Bedroom Furniture, Cocktail glasses, Collectibles, Dining Furniture, Dinnerware, Festive, Floral, Furniture Cushions, Outdoor decor, Outdoor furniture, serve ware, Table linens, TV and Video, Vases, Wall covering, Wall Frames, Wine Storage and Wreaths.

* Are there any products that consistently **underperform** in terms of quantity and revenue?

### Companies:

* What are the top 10 companies in terms of overall **revenue**?

* What are the least 10 companies in terms of overall **revenue**?

### Regions:

* Which **regions** exhibit the highest and lowest sales performance?

* Are there any **regional variations** in demand or customer preferences?
  
* Which **states** exhibit the highest and lowest sales performance?

* Which cities exhibit the highest and lowest sales performance?

* Are there any **correlations** between regional factors (e.g., population density, economic indicators) and sales performance?

 ### Sales Channel:

   The availability and efficiency of distribution channels in a region can affect sales. Kylo's has 4 sales channels: Instore, Online, Distributor, and Wholesale. And this is what their Sales Channel Distribution looks like 

   As can be seen from the donut chart, the In-store channel brought the highest revenue for Kylo's whereas Wholesale brought the least. Let's see how effective these sales channels are across various regions of the United States.

   In the four regions of the United States, Instore (approximately 14%) and Online (around 10%) channels were the most successful. These channels were particularly dominant in the Western and Southern states compared to the Distributor (about 5%) and Wholesale (roughly 3%) channels.

   However, in the Midwestern and Northeastern regions, the contributions of these channels are more evenly matched.

### Correlations and causality:

## Interpretation of Results:
## Reporting: 
## Recommendations for Kylo's A-Z Company:

1. They can plan strategically around the mid-year months (May-August) as well as during festive seasons such as November and December by boosting marketing efforts during the low seasons and capitalizing on the high seasons.

2. They need to identify specific low-performing products and analyze the reasons behind their underperformance. They can consider adjusting pricing strategies, offering targeted discounts, or improving product features. On the other hand they can focus on High-Profit Products and allocate resources and marketing efforts toward these products. They can also optimize inventory management for successful products.

3. To do business with various companies and yield maximum revenue, Kylo's can take the following steps:
  
   - **Segmentation**: Kylo's should categorize their customer base based on revenue performance. Identify high-performing companies and low-performing ones.
  
   - **Focus on Profitability**: Rather than spreading resources across all customers, they should concentrate efforts on the highly profitable companies. These are likely to yield better returns.
  
   - **Strategic Partnerships**: They can collaborate closely with the top-performing companies to strengthen relationships and explore growth opportunities.
  
   - **Performance Metrics**: They should establish clear performance metrics for all clients and regularly assess revenue trends and adjust strategies accordingly.

4. To improve salespeople's performance, Kylo's can take the following steps:
  
   - **Training and Development**: If some salespeople are closing fewer but high-value deals, they might have a knack for landing big clients. The company can consider providing them with further training to enhance their skills. Similarly, those with higher average revenue might be good at consistently closing medium-value deals. Identifying the strengths of each salesperson can help in tailoring training and development programs.

   - **Incentive Structure**: They might also review their incentive structure. If it's solely based on the number of sales, salespeople closing high-value deals might feel unrewarded. A balanced incentive structure that considers both the number of sales and the value of sales could be more effective.

   - **Performance Metrics**: They can consider using a combination of metrics like Revenue Efficiency Score (RES), Sales Conversion Rate (SCR), and Customer Acquisition Cost (CAC) to evaluate a salesperson's performance.

   - **Goal Setting**: They can set clear and specific goals for their salespeople while making sure that these goals align with the company's overall objectives. This could be a mix of revenue targets, number of new customers, retention of existing customers, etc.

   - **Regular Feedback**: Provide the salespeople regular feedback to help them understand their areas of improvement and keep them motivated.

5.  To maximize sales across diverse regions, I'd recommend the following: 
  
    - **Target High-Population Density Areas**: Focus on regions with dense populations, as they offer a larger customer base. Allocate resources for marketing, distribution, and customer engagement in these areas.
  
    - **Customize Marketing Efforts**: Tailor marketing campaigns to suit regional preferences.

    - **Leverage Income Insights**: Recognize that Kylo's A-Z company performs well in regions with medium to low average household income. Adjust pricing strategies and product offerings accordingly.

    - **Evaluate Market Saturation**: Analyze the competitive landscape in each region and identify areas with untapped potential or gaps in the market.

    - **Efficient Distribution Channels**: 2. They can focus on enhancing the Distributor and Wholesale channels to increase revenue in Western and Southern regions. They can consider improving all the channels, with a particular focus on In-store and Online channels in the Midwestern and Northeastern regions.

    - **Product Fit Assessment**:  Understand local needs and preferences and adapt product offerings to align with regional requirements.

## Conclusion:
From the analysis of US Regional Sales Data analysis, I've - 
* Looked into the yearly trend of the sales revenue.
* Identified the high and low performing products, channels, salesperson, customers and regions based on total revenue, profit, number of products etc.
* Discover the patterns and drivers of sales.
* Created an interactive Power BI dashboard to access the data in engaging ways.
* Forecasted revenue for the next 12 months.
* Generate reports and recommendations for improvement and optimization to share with key stakeholders.


## Limitations of the project:
## Future Ideas:
## References:
