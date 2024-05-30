Domain and Data 
You are given a dataset assumed from an e-commerce website that sells sustainable products. 
Their products range from Clothing, Furniture, Home Essentials, Accessories, etc. The 
transaction data is available for 6 months, with 400 unique customers.  
A brief overview of the features in the X matrix (X_train CSV file) is as follows: 
1. Product details – Features include a unique product id, product category (abstracted 
to simpler categories), sub category, and a product rating on a 10-point scale. In 
addition to this, two product scores (columns ‘Product score 1’ and ‘Product score 2’) 
are calculated by the company immediately after every transaction.   
2. Transaction details – Features include a unique transaction number, transaction date, 
a unique seller id, a unique customer id, base price per unit (this can change for 
different transactions of the same product), percentage of discounts applied on the 
base price, percentage of service charge applied on the base price, and the total 
transaction amount per unit quantity. 
3. Customer details – Out of 400 customers in the website till date, 100 customers agreed 
to take a short survey. This resulted in additional features of these 100 customers 
including age, state code (an abstraction of their demographic location), occupation in 
3 levels, and their annual income. The values of these columns for the remaining 300 
customers are hence not available. 
The Y_train CSV file has one column which is the Quantity of the product that was bought in 
each corresponding transaction of X_train.

Project
The company wants to understand the amount of stock that it needs to keep 
available for each product. For this purpose, with the available training data 
(X_train and Y_train), build a prediction model for the quantity of the product 
given other features. Interpret the model’s results: (1) Check which features 
affect quantity the most and the least (2) Provide managerial suggestions for 
the company to improve their business.
