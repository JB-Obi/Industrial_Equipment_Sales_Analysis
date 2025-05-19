# Industrial Equipment Sales Analysis to Achieve Revenue Growth

## Overview
An in-depth SQL analysis of sales data from Frank Industries - a seller of premium tools, machinery, and other components. 

## Business Problem
Critical challenges in understanding sales trends, identifying high-value transactions, and uncovering revenue drivers.

## Objectives
This analysis examines the various products, product categories, sales days, and customer loyalty segments — uncovering revenue trends and purchase behaviors that informed strategic, data-driven recommendations for business growth.
1. Analyze transaction volume and revenue distribution for the month of November across various dimensions (e.g., products, customers, weekdays, days of the month). 
2. Pinpoint high-value transactions and key purchasing patterns. 
3. Highlight performance spikes (e.g., significant revenue increases on specific days). 
4. Provide data-driven insights to inform business decisions, optimize sales strategies, and identify growth opportunities.

Assumptions include the accuracy of transaction data and the exclusion of returns. Deliverables include, in-depth analysis of the data supplied, a detailed written data analysis report, actionable insights, and recommendations for optimizing sales strategies.

## Dataset
- Source: Frank Industries' transaction database
- Format: .csv

## Tools Used
- SQL (PostgreSQL) for querying and analysis
- Highlights:
    - Table creation with Primary Key and other constraints
    - Aggregation, PERCENTILE, and CASE functions for summarizing transactional data
    - Date and time with EXTRACT functions for trend analysis

## Key Insights and Recommendations
1. Products are Well Diversified 
    - Within the time period, 318 products were sold. This clearly shows that the products sold by Frank’s are highly diversified.
    - The diversity was encouraged. However, further analysis was recommended as a crucial business step, to analyze the inventory and procurement data with reference the sales data, to identify less profitable and possibly stagnating products.  

2. Impressive Customer Base 
    - The business successfully attracted 3,003 customers within 28 days, demonstrating strong customer reach and market presence. This solid customer base provides a strong foundation for future growth and increased revenue potential. 
    - To sustain and build on this success, the recommendation was to: 
      - Continue implementing strategies that drive customer acquisition and retention.
      - Explore opportunities for enhanced customer engagement, such as personalized promotions, loyalty programs, or targeted marketing campaigns to maintain momentum and encourage repeat purchases.

3. A Good Number of Transactions Draw in High Revenue 
    - An examination of the records where the unit price and quantity sold both exceed their averages reveal that 23.3% of transactions (nearly 25% = a quarter) involved number of units sold and unit prices whichexceeded the average threshold. 
    - Further analysis was recommended, to ensure that the revenues are effectively translated into profits.

4. High Revenue Generation Across Products 
    - The analysis of revenue generated and sales quantity by product unearths a key insight that products with low volume sales also generate revenues which exceed the average revenue generated. This shows a balanced measure of revenue generation across products, highlighting a healthy product catalogue. 
    - Frank’s was encouraged to continue with the products being sold, and to ensure that advertising efforts are continually spread across products.

5. Weekday Trends in Transaction Volume and Revenue 
    - The analysis uncovers that Friday consistently outperformed other days in both transaction volume and total revenue generation, indicating higher customer engagement and spending on this day. Conversely, Monday experienced the lowest revenue and transaction volume, signaling reduced sales activity.
    - The recommendation was to leverage the high customer activity on Fridays by implementing promotional campaigns or discounts to further boost sales. Targeted marketing with incentives were also recommended as a solution to improve transaction volume and revenue on this day.

6. Customer Engagement 
    - While most customers made only 1 or 2 purchases, a select few returned consistently, with 3 or 4 purchases recorded over the period. Returning customers, such as Customer IDs 6760, 5944, and 2566, could be considered more loyal or highly engaged buyers. 
    - It was then recommended to improve Engagement with Frequent Buyers by identifying customers with high purchase frequency (e.g., IDs 6760, 5944, and 2566) and giving them incentives to ensure they continue purchasing. Offering tailored promotions could strengthen their loyalty further. 

7. Revenue Concentration 
    - A significant portion of revenue is driven by high-value customers who spent over ₦5,000,000. The top 3 customers alone (IDs 2825, 6760, and 6552) contributed substantial revenue, indicating that a small subset of customers is responsible for a large share of sales. 
    - Based on this discovery, a strong recommendation was to develop loyalty programs, personalized discounts, or premium offers to retain and reward high-value 
customers (e.g., IDs 6760, 2825, and 6552) who significantly contribute to revenue. 
