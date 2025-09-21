# Supermarket Profit Dashboard

## Project Overview
The objective of this project is to analyze the profits of a U.S. supermarket company. Using a fictitious dataset, the goal is to build a dashboard that is simple, yet functional and visually appealing.

## Data Source
- [Kaggle - Superstore Dataset](https://www.kaggle.com/datasets/roopacalistus/superstore)  
- License: GNU Lesser General Public License (LGPL)

## Data Preparation
Explain the main steps taken in Power Query:
- Column renaming (e.g., Segment → Customer Type).  
- Removing redundant fields (e.g., Country).  
- Cleaning operations (Trim, Clean).  
- Verifying data quality with Column Profile, Column Quality, and Column Distribution.

## Data Model
- Mention that the dataset consists of a single fact table.  
- No date dimension was created as the dataset does not include a date column.  
- Visuals are based directly on existing fields (Region, City, Customer Type, Category, Sub-Category).

## Dashboard Design
The dashboard was designed in Power BI with a focus on simplicity and clarity:
- Four KPI cards at the top displaying: Average Discount, Total Profit, Total Sales, and Average Quantity Sold.  
- A column chart showing the Top 5 Sub-Categories by Profit.  
- A bar chart displaying Total Profit by Category.  
- A pie chart showing Total Profit by Ship Mode.  
- A decomposition tree breaking down Total Profit by Customer Type, Category, and Sub-Category.  
- A map of the United States highlighting states, designed to work with the Region slicer for filtering and emphasis.  
- A single slicer for Region to drive interactivity.  
  

## Key Insights
- The technology category drives the highest profit.  
- Furniture has the lowest profitability.  
- Consumers represent the most profitable customer type.  
- Standard Class shipping generates the majority of profit.  
- The Furniture - Tables sub-category incurs losses of approximately 17K.  
- Copiers are the most profitable sub-category across all three customer types.  
- The West region generates the highest profit, with approximately 108K.  
 
## Recommendations
- Reevaluate the Furniture - Tables sub-category, which is generating losses of approximately 17K. Consider reducing discounts, renegotiating supplier contracts, or shifting focus to more profitable furniture items.  
- Invest in promoting and expanding the Copiers sub-category, as it delivers the highest profit across all customer types. Targeted marketing campaigns or bundling strategies could further increase sales in this area.  
- Strengthen operations and marketing efforts in the West region, which generates the highest profit (around 108K). Insights from this region could be applied to underperforming regions to replicate success.  
- Monitor product-level profitability across categories to identify and phase out consistently unprofitable items, while reinvesting in high-margin products.  

## How to Use
Explain how someone can explore the dashboard:
- Open the `.pbix` file in Power BI Desktop.  
- Use the visuals (Slicer, charts, map) to filter results.  

## Project Files
- (docs/Retail_SupermarketPBI.pbix) – Power BI dashboard file.  
- `Retail Supermarket PBI.pdf` – Exported static version for quick preview.  
- `README.md` – Project documentation.  


