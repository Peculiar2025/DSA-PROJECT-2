#  Amazon Product Review Dashboard

A data analysis and visualization project to explore Amazon product reviews, pricing, discounts, and ratings using Excel and Power BI.

##  Project Overview

This dashboard answers critical business questions such as:
- What is the average discount percentage by product category?
- Which products have the highest average ratings?
- How does actual price compare to discounted price?
- What is the total potential revenue per category?
- Which products have fewer than 1,000 reviews?

##  Tools Used

- Microsoft Excel (for data cleaning, pivot tables, helper columns)
- Power BI (for dashboard design & visualization)


##  Key Business Questions Answered

1. Average Discount Percentage by Product Category  
2. Total Number of Products per Category  
3. Total Number of Reviews per Category  
4. Products with the Highest Average Ratings  
5. Average Actual Price vs Discounted Price by Category  
6. Products with the Highest Number of Reviews  
7. Products with Discount ≥ 50%  
8. Distribution of Product Ratings  
9. Total Potential Revenue by Category  
10. Unique Products per Price Range Bucket  
11. Relationship Between Rating and Discount Level  
12. Products with Fewer Than 1,000 Reviews  
13. Categories with Highest Discounts  
14. Top 5 Products Based on Rating × Review Count

Each question is addressed using Pivot Tables, Calculated Columns, and Excel Formulas.


# AMAZON DATA REVIEW
##This project is detailed excel dashboard analysis of an e- commerce product dataset.It explore product rating, pricing patterns, discount and review from customer
# DATA SOURCE
Digital skill Africa(DSA
# STEPS
##DATA CLEANING ACTION
##
1. Standardized Product Name with =Left function and i created a helper column
2. Proper case : I used proper function to make the name to appear well by using another helper column
3. Category splitting was done with Delimiter and i created extra 4 column to split the product into category
4. i also converted Text to Number
5. I also created price range bucket
with if function; IF(Discounted Price < 200, "<₹200",
   IF(Discounted Price <= 500, "₹200–₹500", ">₹500"))
6. i also calculated Discount percentage by applying if function; =If(discount percentage>0.5,1,0)
# ANALYSIS TASK
##Total product= 1350
## DASHBOARD OVERVIEW

![amazon case real  snapshot](https://github.com/user-attachments/assets/76114aa7-374b-4931-9c20-8e3a4408c87f)
# CHART

![CHART 3](https://github.com/user-attachments/assets/fdda82b3-cec6-4dcb-9edd-c40e60f304b1)

![CHART 2](https://github.com/user-attachments/assets/42312a47-105a-45a6-b578-510c92fe0a7b)

![CHART 1](https://github.com/user-attachments/assets/eab49d7c-60a0-43de-9a50-9d09363dee70)
