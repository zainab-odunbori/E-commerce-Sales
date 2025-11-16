# E-Commerce Sales Analysis

The E-commerce Sales analysis was done to explore and analyze key insisghts from a dataset containing details about Sales of a Company, including the region the sales was made, the Category of the Product, Quantity Sold and Cost.

## Tools

Excel 
Pivot Table and Pivot Chart in Excel

### Cleaning and Preprocessing the Dataset
To ensure data intergrity:
1. Import the files into EXCEL 
2. Check for missing Values
3. Check for duplicates (No duplicates)
4. Converted into table to get better view at the dataset and make it more organised
5. Added two column to further explore the dataset.
6. The two columns added was for Year and Month respectively


### Exploratory Data Analysis (EDA)

Key Questions

- How was the Sales Performance in 2023 and 2024
- What product has the highest Sales by Product and Category
- Which product gave the highest Sales
- What Month gave the highest Sales and Lowest Sales in 2023 and 2024
- What year gave the highest profit

  ### Data Analysis
  The Year and Month table was added to help in further analysis.
  Formular Used:
  TEXT [(@Date),"MMM"]
  TEXT [(@Date), "YYYY"]

  Pivot Table was used for the analysis:
  Insert Pivot Table
  The Pivot table was used to Calculate the KPIs; Sales, Quantity, Cost and Profit
  The dataset was formated using the formular;
  [>=1000000]$0.0,,"M";[>=1000]$0.0,"k";0

  Pivot Table was also used to Calculate YOY Change
  (current Year - Previous Year)/Previous Year
  This formular was used to Calculate:
  Sales Year On Year Growth
  Cost Year On Year Growth
  Quantity Year On Year Growth

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

2. The Product with the highest Sales in 2024 is Monitor which is in the Electronics Category, while Monitor had the lowest Sales in 2023.
The Product with the highest Sales in 2023 was Keyboard which was the product with the lowest Sales in 2024
   
   
   
