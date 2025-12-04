# Car-Sales-Data-Analysis

# INTRODUCTION
This project focuses on analyzing car sales performance across different companies, regions, body styles, and customer preferences. The goal was to build an interactive dashboard that provides insights into Year-to-Date (YTD) and Month-to-Date (MTD) sales, average pricing trends, color preferences, and dealer performance. By transforming raw sales data into a clear and visually compelling dashboard, this project demonstrates strong data analytics skills, including data cleaning, modeling, DAX calculations, and interactive report design in Power BI.
The dashboard serves as a decision-support tool for stakeholders, helping them understand key business drivers, identify top-performing regions and products, and evaluate changes in sales patterns over time. It reflects my ability to work with real-world datasets, uncover insights, and communicate findings effectively.

# ANALYSIS

# Sales Performance Overview
YTD Total Sales reached 371M, showing a strong yearly performance.
MTD Total Sales is 54M, indicating healthy ongoing sales momentum.
13K cars sold YTD, with 1,921 cars sold MTD, showing steady customer activity.

<img width="1231" height="121" alt="image" src="https://github.com/user-attachments/assets/f0f0d2ea-b94b-44f4-8c02-cf98cd603c5b" />


# Pricing Trends
The YTD Average Price is 27.99K, while the MTD Average is 28.26K.
A slight YOY decrease of -0.79% in average price shows minor drops in pricing compared to the previous year.
Despite this, total revenue remains strong due to high sales volume.

<img width="540" height="304" alt="image" src="https://github.com/user-attachments/assets/3761616a-c10e-4c90-8025-12bf371afc6d" />


# Body Style Performance
SUVs lead with 100M in YTD sales, making them the most profitable segment.
Hatchbacks, Sedans, Passenger cars, and Hardtops follow respectively.
This indicates a clear customer preference for SUVs.

<img width="335" height="298" alt="image" src="https://github.com/user-attachments/assets/4bab55a2-2759-453b-9655-43ed2bb5f600" />


# Regional Performance
Top-performing dealer regions include Austin (117M), Janesville (106M), and Scottsdale (96M).
These regions significantly outperform others, suggesting strong demand concentration.

<img width="540" height="299" alt="image" src="https://github.com/user-attachments/assets/2da60d37-9343-4516-928b-f4a843782929" />


# Customer Preferences by Color
Green-colored cars account for 48% of all sales, making it the most popular choice.
Black cars follow at ~33% and red at ~19%.
Color preference can guide inventory and marketing decisions.

<img width="346" height="311" alt="image" src="https://github.com/user-attachments/assets/a521e6a7-d162-447c-90cd-67716453b9f5" />


# Company-Level Insights
Manufacturers like Ford, Chevrolet, BMW, and Audi contribute significantly to the overall sales.
Companies with higher sales also tend to maintain competitive average pricing.

<img width="484" height="283" alt="image" src="https://github.com/user-attachments/assets/a1dcf026-1e34-44d7-b2a1-0677ddbad967" />


# Weekly Sales Trend
The weekly sales chart shows a generally upward trend with peaks toward the end of the year (around week 45–50).
Suggests seasonality or end-of-year promotional effects.
Overall, the analysis shows strong yearly performance, clear customer preferences, and identifiable opportunities for better pricing and regional allocation strategies.

# PROCESS USED
# 1. Data Collection
The dataset was sourced from Car Sales xlsx and included fields such as:
Price, Dealer Region, Body Style, Color, Company, Date, Transmission, Customer and Dealer Info

# 2. Data Cleaning
Performed in Power Query:
Removed duplicates and irrelevant columns.
Corrected data types (date, numeric, text).
Standardized categories (body style, region, color).
Handled null or missing values where necessary.

# 3. Data Modeling
Created a Star Schema structure with:
Fact table: Car Sales
Dimension tables: Calendar table, Company, Region, Body Style

Established relationships:
Date → Calendar Table

4. DAX Calculations
Created key measures such as:
YTD Total Sales, MTD Total Sales, YTD Cars Sold, Average Price, YOY Price Difference
Weekly and Monthly Aggregations
 These measures enabled dynamic analysis across time and filters.

5. Visualization Design
- Used Power BI card visuals for high-level KPIs.
- Used bar and column charts for body style, region, and company-level analysis.
- Used a donut chart for color distribution.
- Used a line chart for weekly sales trends.
- Applied custom theming and color rules to improve readability and storytelling.

6. Interactivity Enhancements
Added slicers for:
Year
Company
Gender
Transmission
ealer Region
Added drill-through capability and dynamic titles.
Enabled conditional formatting for positive/negative YOY differences.

<img width="1920" height="1080" alt="Screenshot (256)" src="https://github.com/user-attachments/assets/36e863d1-c11a-44ba-9456-fe54f4e74a33" />

<img width="1920" height="1080" alt="Screenshot (250)" src="https://github.com/user-attachments/assets/8406ced7-5be9-46a2-b7f2-628efaaea035" />

 INSIGHTS
# Strong Year-to-Date (YTD) Sales Performance
YTD Total Sales: 371M
YTD Total Cars Sold: 13K
Sales volume and revenue appear strong and consistent across months.

# Positive Month-to-Date (MTD) Performance
MTD Total Sales: 54M
MTD Cars Sold: 1,921
Indicates steady sales momentum continuing into the current month.

# YoY Sales Difference
Average Sales YOY shows -0.79%, indicating a slight decline in the average selling price compared to last year.
However, total YTD sales remain high, meaning volume is compensating for the drop in average price.

# Body Style Performance
SUVs lead with 100M, followed by Hatchback (83M), Sedan (74M), Passenger (63M), and Hardtop (51M).
SUVs are the strongest revenue driver and likely the most in-demand segment.

# Car Sales by Color
Green (48%) is the highest contributor to car sales volume (~6K units).
Followed by Black (~4K) and Red (~3K).
Indicates strong preference for certain car colors, which can influence inventory decisions.

# Dealer Region Impact
Top-performing regions include:
Austin (117M)
Janesville (106M)
Scottsdale (96M)
These markets significantly drive total revenue and may have stronger consumer demand.

# Company-Level Performance
Top companies by YTD Sales:
Ford (25M+)
Chevrolet (27M+)
BMW (17M+)
Companies with higher car sales tend to also have strong average prices.

# Weekly Performance Trend
Weekly sales show a generally increasing pattern with peaks near week 45–50, suggesting strong late-year buying behavior—possibly seasonal.

# RECOMMENDATIONS

# Strengthen Focus on High-Performing Body Styles
Since SUVs generate the highest revenue, allocate more marketing budget, promotions, and inventory toward SUVs.

# Address Slight Drop in YOY Average Price
- The YOY drop in average price suggests the need to:
- Review discount strategies
- Assess pricing competitiveness
- Evaluate whether lower pricing is necessary or causing unnecessary revenue loss
  
# Expand Operations in High-Performing Regions
Austin, Janesville, and Scottsdale are outperforming others.

Consider:
- Increasing dealer partnerships
- Boosting inventory in these regions
- Running localized campaigns

# Optimize Color Inventory
- Since green-colored cars dominate sales, ensure adequate stock levels.
- Reduce inventory holding of low-demand colors to avoid slow-moving stock.

# Maintain Strong Sales Momentum
The MTD performance suggests buyers are active—launch short-term promotions to push sales above monthly expectations.

# Target Underperforming Brands or Regions
Use targeted discounts or promotional campaigns to boost sales in regions with lower YTD revenue.

# CONCLUSION
The Car Sales Dashboard reveals a healthy sales environment, with strong YTD revenue, high car sales volume, and a positive MTD performance. SUVs and specific regions like Austin remain major revenue drivers, while color preference trends offer valuable inventory insights. Although the YOY average price slightly declined, overall sales remain robust due to strong volume performance.
By optimizing regional focus, adjusting pricing strategy, and leveraging high-performing car categories, the company can continue strengthening its market position and improving profitability. The dashboard demonstrates an effective blend of volume-driven growth and strategic opportunities for future improvement.

