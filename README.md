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
1. Diverse Product Range
    - Within the 28-day period, 318 unique products were sold — demonstrating a highly diversified product offering at Frank’s.
    - While product variety is a strength, further analysis of inventory and procurement data was recommended to pinpoint underperforming or stagnant items, ensuring efficient stock management and profitability.

2. Strong Customer Base
    - The business attracted 3,003 customers within just 28 days, showcasing strong market reach and potential for sustained growth.
    - To maintain and expand this momentum, the recommendations were to:
        - Continue executing customer acquisition and retention strategies.
        - Introduce loyalty programs, personalized promotions, or targeted marketing to deepen engagement and encourage repeat purchases.
3. High-Value Transactions
    - 23.3% of all transactions had both unit price and quantity sold above their respective averages — revealing that a substantial portion of sales contributes significantly to revenue.
    - A follow-up profitability analysis was advised to confirm whether high-revenue transactions also deliver strong margins.

4. Revenue Balance Across Product Lines
    - Some products with lower sales volumes still generated above-average revenue, pointing to a healthy and balanced product mix.
    - The business is encouraged to maintain its current product range while ensuring marketing efforts are evenly distributed across categories.

5. Weekday Sales Trends
    - Fridays recorded the highest transaction volume and total revenue, while Mondays saw the lowest.
    - Recommendations:
        - Boost Friday sales further through limited-time offers or end-of-week campaigns.
        - Implement Monday-specific promotions to stimulate early-week demand.

6. Customer Loyalty Patterns
    - Although most customers purchased once or twice, a few (e.g., Customer IDs 6760, 5944, 2566) made 3–4 purchases within the period, signaling loyalty or high engagement.
    - Suggested action:
        - Reward repeat buyers with exclusive deals or loyalty incentives to reinforce continued patronage.
7. Revenue Concentration Among Top Buyers
    - High-value customers (those who spent over ₦5,000,000) were responsible for a major share of total revenue. The top 3 customers alone (IDs 2825, 6760, and 6552) made a notable impact.
    - Recommendation:
        - Develop VIP retention strategies such as premium loyalty programs or personalized offers to nurture this profitable segment.
