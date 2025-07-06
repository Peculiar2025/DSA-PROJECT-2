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
## DASHBOARD OVERVIEW

![amazon case real  snapshot](https://github.com/user-attachments/assets/76114aa7-374b-4931-9c20-8e3a4408c87f)
# CHART

![CHART 3](https://github.com/user-attachments/assets/fdda82b3-cec6-4dcb-9edd-c40e60f304b1)

![CHART 2](https://github.com/user-attachments/assets/42312a47-105a-45a6-b578-510c92fe0a7b)

![CHART 1](https://github.com/user-attachments/assets/eab49d7c-60a0-43de-9a50-9d09363dee70)
