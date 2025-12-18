# End-to-End-Sales-Analysis
End-to-end sales analytics project using Python to analyze multi-month sales data and generate business insights.
# 📊 Sales Analysis Using Python

#  About This Project
This project is a simple and practical sales analysis built using Python.  
I worked with three months of sales data (October, November, and December 2019) to understand how a business is performing.

The goal of this project was not just to write code, but to answer real business questions like:
- Which month had the highest sales?
- Which products bring the most revenue?
- Which cities perform the best?
- At what time do customers place most orders?

This project was created as part of my Business Analytics learning and is suitable for beginner to intermediate level analysis.



# What I Wanted to Achieve
- Combine multiple sales files into one dataset  
- Clean messy and incomplete data  
- Calculate sales (revenue) properly  
- Analyze trends in sales, products, cities, and time  
- Present insights using simple graphs  



# Tools Used
- Python  
- Pandas (for data handling)  
- Matplotlib (for graphs)  
- Jupyter Notebook  

# About the Data
The data contains sales records for three months:
- October 2019  
- November 2019  
- December 2019  

Each file includes:
- Order ID  
- Product name  
- Quantity ordered  
- Price of the product  
- Order date and time  
- Purchase address  

All files have the same structure, which made it possible to merge them together.

# What I Did (Step by Step)
1.   Loaded the data
   - Read all sales CSV files from a folder
   - Combined them into one table

2.   Cleaned the data
   - Removed empty rows
   - Fixed date formatting issues
   - Converted quantity and price columns to numbers

3.   Created new columns
   - Calculated total sales for each order
   - Extracted month, hour, city, and price category

4.   Analyzed the data
   - Monthly sales trend
   - Top-selling products
   - Top cities by sales
   - Orders by hour of the day
   - Average order value
   - Products frequently bought together

5.   Visualized the results
   - Bar charts for sales, products, and cities
   - Line chart for hourly order trends


# Key Findings
- December had the highest sales, likely due to festive demand  
- Expensive products generated more revenue than cheaper ones  
- Big cities like San Francisco, Los Angeles, and New York performed best  
- Most orders were placed in the afternoon and evening  
- Some products are often purchased together, which can help in bundling  

# Business Takeaways
- Businesses should prepare more stock during high-demand months  
- Marketing should focus on high-performing cities  
- Ads should be scheduled during peak customer activity hours  
- Product bundles can help increase total sales per order  
