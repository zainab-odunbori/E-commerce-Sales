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

A custom number format was applied for readability:
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

### Results 
Summary of key insights from the E-commerce Sales Analysis
1. The total Sales of 2024 was $475.6K while the total Sales of 2023 was 365.6k
The total Cost of 2024 was $64.0k while the total cost of 2023 was 57.5k
The total Profit of 2024 was $411.6k while the total Profit of 2023 was $308.1k
The total Quantity Sold in 2024 Was 899 while the Quantity Sold in 2023 was 724
 The major pattern noticed is the increase in all the major Key performance Index in 2024, Sales, Cost, Profit and Quantity

2. The Product with the highest Sales in 2024 is Monitor which is in the Electronics Category which had the lowest Sales in 2023.
The Product with the highest Sales in 2023 was Keyboard which was the product with the lowest Sales in 2024 in the Accessory Category.

3.  There is an opposite relationship in the revenue of 2023 and 2024, this can be seen in the monthly revenue trend and the months that showed these most were: February 2023 & 2024, March 2023 & 2024, April 2023 & 2024.

### Recommendation

### Limitation
   
   
   
