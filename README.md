# E-Commerce Sales Analysis

The E-commerce Sales Analysis was conducted to explore and uncover key insights from a dataset containing Sales records, including the region where each sale was made, the product category, quantity sold, and cost.

## Tools

Excel 
Pivot Table and Pivot Chart

### Cleaning and Preprocessing the Dataset
To ensure data intergrity:
1. Import the files into EXCEL 
2. Check for missing Values
3. Check for duplicates (None were found)
4. Converted the dataset into an Excel Table for better structure and easier formatting.
5. Added two new columns (Year and Month) for deeper time-based analysis.
6.Extracted Year and Month using:
=TEXT([@Date], "MMM")
=TEXT([@Date], "YYYY")


### Exploratory Data Analysis (EDA)

Key Questions

- How was the Sales Performance in 2023 and 2024?
- What product has the highest Sales by Product and Category?
- What Month gave the highest Sales and Lowest Sales in 2023 and 2024?
- What year gave the highest profit?

  ### Data Analysis
Pivot Tables were used to calculate the main KPIs:

Sales
Quantity
Cost
Profit

A Custom number format was applied for readability:
[>=1000000]$0.0,,"M";[>=1000]$0.0,"k";0

Year-on-Year (YoY) performance was calculated using:

Current Year – Previous Year / Previous Year
	​
This formula was used for:

Sales YoY Growth
Cost YoY Growth
Quantity YoY Growth

### Data Visualization
   Pivot Chart was used for Data Visualization
   ![Dashboard](Exceldashboard1.png)

### Results/ Key Insights
 1. Overall Yearly Performance

Total Sales:
2024: $475.6K
2023: $365.6K

Total Cost:
2024: $64.0K
2023: $57.5K

Total Profit:
2024: $411.6K
2023: $308.1K

Total Quantity Sold:
2024: 899 units
2023: 724 units

Insight: All major KPIs — Sales, Cost, Profit, and Quantity — increased significantly in 2024, indicating strong year-over-year improvement.

2. Product Performance

2024 Highest-Selling Product: Monitor

Category: Electronics

Note: It had the lowest Sales in 2023.

2023 Highest-Selling Product: Keyboard
Category: Accessories
Note: It recorded the lowest Sales in 2024.
This shows a contrasting trend in product preference between both years.

3. Revenue Trend Relationship

There is an inverse trend (opposite movement) between the monthly revenue of 2023 and 2024.
This contrasting trend is most visible in:

March 2023 vs 2024
July 2023 vs 2024
September 2023 vs 2024

Where revenue increased in one year and decreased in the other.

### Recommendation

1. Focus more marketing and inventory allocation on products with rising demand (e.g., Monitors).

2. Investigate the sharp shift in product performance to understand customer behavior changes.

3. Analyze months with poor performance to identify seasonal patterns or operational issues.

3. Consider cost-optimization strategies, since cost also increased year-over-year.


### Limitation

1. The analysis is limited to the available dataset and may not include all sales channels.

2. External factors (market trends, pricing changes, promotions) were not included.

3. The dataset covers only two years, limiting long-term trend analysis.
   
   
   
