# Retail Supermarket Dashboard

## Project Overview
Briefly describe the purpose of the project and the dataset used. Mention that the goal was to create a simple but visually attractive Power BI dashboard analyzing supermarket sales and profit across regions, customer types, and product categories.

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
- Slicers are based directly on existing fields (Region, City, Customer Type, Category, Sub-Category).

## Dashboard Design
- Layout and KPI placement.  
- Visuals included (Total Sales, Profit by Region, Profit by Category, Top Sub-Categories, Ship Mode analysis, etc.).  
- Color palette and formatting choices.  
- Slicers for interactivity.  

## Key Insights
Summarize 3–5 key findings from the dashboard. For example:
- Technology category drives the highest profit.  
- Furniture has the lowest profitability.  
- Consumers represent the most profitable customer type.  
- Standard Class shipping generates the majority of profit.  

## How to Use
Explain how someone can explore the dashboard:
- Open the `.pbix` file in Power BI Desktop.  
- Use the slicers (Customer Type, Category, Sub-Category) to filter results.  

## Project Files
- `Retail Supermarket PBI.pbix` – Power BI dashboard file.  
- `Retail Supermarket PBI.pdf` – Exported static version for quick preview.  
- `README.md` – Project documentation.  

## Acknowledgments
Credit the dataset source and mention the license.
