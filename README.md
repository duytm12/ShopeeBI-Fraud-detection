# ShopeeBI-Fraud-detection
An E-commerce platform - Shopee launched a promotion program from 10/30/2019 to 11/2/2019. The goal of the analysis was to identify which buyers and shops tried to leverage and took advantages of the promotion program.

I. Data from table transaction_data:
- txt_time: Time when a transaction occured
- txt_date: Date when a transaction occured
- order_id: Order ID
- uid: Buyer/ User ID
- shop_id: Shop ID
- shop_owner_uid: Shop Owner ID
- gmv: Gross monetary value of a transaction
- rebate: Cash back based on GMV

II. Steps:
  1. Load data into Power BI
     
  2. Generate Overview dashboard
     - 2.1. Total Customers = Count distinct uid
     - 2.2. Total Revenue = Sum gmv
     - 2.3. Total Orders = Count order_id
     - 2.4. Using basic statistics, calculate Min, Median, Average, and Max of Orders

  3. Compare GMV vs Rebate

  4. Fraud detection
     - 4.1. Checked the shops with the most orders and most more-than-one-time orders with the maximum rebate
     - 4.2. Checked the users who were trying to buy from the same shops and maxed out the rebate on every order
     - 4.3. Matched the results to see which shops were trying to cooperate with users to take advantage of the promotion programs


III. Tools:
- Power BI Desktop
- PowerPoint
