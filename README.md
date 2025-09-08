# Analyzing Discount Impact on Profit
## Goal
Identify how discount affects profit and detect unprofitable products/regions.
## Data
- Source: Kaggle
- Dataset: Superstore Dataset (9994 records, 21 columns)
- Link: [Superstore Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)
## Tools and Technique
Power BI: Query Editor, DAX, Visualization
## Process
1. Data cleaning & transformation by Query Editor in Power BI
2. Built a Star Schema

Image of data model: [Sales Analysis Data Model.jpg](https://github.com/trieunh10-portfolio/Portfolio/blob/main/Sales%20Analysis%20Data%20Model.jpg)

4. Data exploration

DAX Formula: [DAX Formula.md](https://github.com/trieunh10-portfolio/Analyzing-Discount-Impact-on-Profit/blob/main/DAX%20Formula.md)

5. Dashboard design & insights
(File Power BI)

## Results
- Profits gradually increased from 2015 to 2017, while revenue experienced a slight decline from 2014 to 2015.  
- The region with the highest sales revenue is the West, where tech products generate the most revenue and profit.  
- Revenue and profit remain stable with discounts ranging from 5% to 20%. However, when discounts exceed 20%, the benefits begin to decrease, potentially leading to losses.  
- The West also has the highest profit, with an average discount of 15.34%. The Central region has the highest average discount at 16.54%, but its profit ranks third out of four regions.  
- In the sub-categories, furniture has the highest average discount at 17.4%, but some products, such as tables, bookcases, and supplies, show significant losses.  
## Insights
- High discount levels can help increase revenue, but not always result in profit. Many products have high revenue but still incur losses
- The optimal discount range to maintain profitability is between 10% and 20%
- Control the discount policy for each Sub-Category. For example, limiting the discount on products in the Furniture group, because even a discount of around 10% can easily lead to negative profits
- The Central region shows a high average discount level but has a low profit margin -> sales policies should be adjusted based on regional performance

  
