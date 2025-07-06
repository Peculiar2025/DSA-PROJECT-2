# AMAZON DATA REVIEW
## This project is detailed excel dashboard analysis of an e- commerce product dataset.It explore product rating, pricing patterns, discount and review from customer across various products.
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
#DASHBOARD SCREENSHOTS

