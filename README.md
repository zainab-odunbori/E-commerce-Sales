# E-Commerce Sales Analysis

The E-commerce Sales analysis was done to explore and analyze key insisghts from a dataset containing details about Sales of a Company, including the region the sales was made, the Category of the Product, Quantity Sold and Cost.

## Tools

Excel 
Pivot Table and Pivot Chart in Excel

### Cleaning and Pre-processing the Dataset
To ensure data intergrity:
1. Import the files into EXCEL 
2. Check for missing Values
3. Check for duplicates (No duplicates)
4. 
5. Converted into table to get better view at the dataset and make it more organised
6. Added two column to further explore the dataset.
7. The two columns added was for Year and Month respectively


### Exploratory Data Analysis (EDA)

Key Questions

- What was the Sales Performance in 2023 and 2024
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
  Sales YOY Growth
  Cost YOY Growth
  Quantity YOY Growth

### Data Visualization
   Pivot Chart was used for the Visulization
   ![Dashboard](Excel Dashboard 1.PNG
   
