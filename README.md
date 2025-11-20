### E-Commerce-Analysis-Dashboard
A Project on  analyzing  customer demographics and purchasing behavior. By examining sales trends across age groups, customer segments, and actionable insights that improve customer engagement and optimize sales strategies to drive business growth.

### DATA SOURCE
The primary dataset was gotten from https://1drv.ms/w/c/c883cf74156d887c/IQArqkaD3OcFTYqF3bXG7F3XAafMPkKH9MST8GUx-peWv2c?e=p33fio


### TOOLS & TECHNIQUES
  The tools used for this project are;
  - Microsoft Excel: Data cleaning and preparation
  - Microsoft Power Bi: Data modeling, DAX calculations, relationships, slicers and KPI visuals.
  
 
 ### OBJECTIVES/KEY PERFORMANCE INDICATORS

OBJECTIVES
- Understand customer demographics and purchasing behavior.
- Analyze product performance to identify best-selling and underperforming items.
- Detect patterns in abandoned carts to improve conversion rates.
- Provide insights for fraud detection and secure transactions.


  ### DATA CLEANING
 Data Cleaning Process using Excel(Power Query)
- I handle missing or inconsistent values in fields required
- I dropped some columns not relevant for the analysis.
- I removed duplicates
- I cleaned inconsistent writing formats to normalize data.

Data Metrics used
- Total sales, Avg sales, total customers, total products.


### DASHBOARD & INSIGHTS
1. Customer demographics dashboard

- Analyzing purchasing behavior by Gender: Females made the highest number of purchases with 4,445 transactions (34.25%), followed by Other (4,358 – 33.58%) and Males (4,174 – 32.16%).In terms of Total Sales, Females generated ₦1.15M (34.91%)slightly ahead of Males at ₦1.1M(33.34%) with an and Others at ₦1.05M(31.76%).Females has a higher avg sale per transaction compared to other genders.(Females: 259.21, Male: 252.51, other:251.13).         
KEY INSIGHTS:  Female customer generate the highest transaction volume and total sales showing slightly higher purchasing power compared to other genders. This indicate product alignment with female buyers.

- Analyzing Purchasing behavior by Age Group: Analyzing total sales by age group helps us identify which age group generates more revenue.
50+ Age group generates the highest sales of 1.69M with a higher transaction of 6622, 18-25 has a higher avg sale per transaction of 264.63 despite generating the lowest total sales.

- Analyzing Purchasing behavior by Customer Segment & Gender: Analyzing purchasing behavior across four customer segments (New, VIP, Regular, and Occasional) by gender. Female customers consistently lead in transaction count across all segments, with the highest activity in the New segment (35.76% of transactions), New customers (Female) generated the highest sales ₦302K(35.71%) among that segment. Regular female customers  has the highest avg sale per transaction (268.59) which implies they spend more per transaction. 

- Analyzing Purchasing behavior by Loyalty_Program_Member: Loyal members generated ₦1.7M(51.5%) slightly higher than non-members at ₦1.6M(48.5%).
Both loyal & Non-members had nearly equal transactions.(Loyal members:6640,Non members:6637)
KEY INSIGHTS: The loyalty program appears to slightly boost purchasing power.

- Analyzing Purchasing behavior by payment method & customer segment: Analyzing payment methods across both total sales and transaction volume.
PayPal: Highest total sales (₦841.83K) and avg.sale (₦257.28) with fewer transactions. 
Credit card: Highest transactions(3,291) but lower sales (₦824.37K) and avg.sale (₦250.49)
Key Insight: This reveals that PayPal users tend to make fewer but higher-value purchases, indicating a segment with slightly higher purchasing power and credit card users purchase more frequently.

<img width="1096" height="629" alt="Screenshot 2025-11-20 204319" src="https://github.com/user-attachments/assets/29c7b531-a7f5-46c4-acbe-532bcf656119" />

2. Product Analysis
- Best Selling and Underperforming Products:
Analyzing total sales by product item reveals both top-selling and underperforming products.
Blazer has the highest revenue at ₦0.36M with 1,393 transactions.
Dress has the highest transaction count of 1,402, but slightly lower revenue of ₦0.34M making it our best seller products.
Shorts has the lowest revenue (₦0.29M) and lowest transaction count(1099) making it our underperforming products.

- Product Performance Across Customer Gender:
Female customers buy more sneakers, jeans, t-shirts, blazers, and shorts.
Male customers purchase more jackets, caps, and handbags.
Each category leans clearly toward a specific gender, making targeting easier for marketing and product placement for each gender.

- Product Performance Across Age Groups:
18–25: Strong interest in casual items like sneakers, shorts, t-shirts, and sandals.
26–35: More balanced but slightly higher on blazers, dresses, handbags, and jackets.
36–50 & Above: Prefer classic items such as jackets, blazers, and sandals.
Age influences style preference, so tailoring promotions by age bracket can increase conversions.

<img width="1105" height="642" alt="Screenshot 2025-11-20 204234" src="https://github.com/user-attachments/assets/824e8680-b8b6-4982-93ca-20d19c43c0b2" />

3. Cart Status analysis
- Cart status by Age Group & Device Type:
Cart abandonment is consistently high across all age groups, averaging around 50% on every device.
The 26–35 age group records the highest mobile abandonment, 18–25 age group maintains slightly higher purchase rates on tablet.
Customers aged Above 50 show stable behavior and has a slightly higher purchase rates on desktop.
Insight: Since abandonment remains high across all demographics, the issue is likely tied to the general checkout experience rather than a specific age group. Improving the mobile checkout flow should be prioritized, given the higher drop-off among mobile users aged 26–35.

- Customer behavior by Cart Status: This analysis explains that 50.48% customers abandoned there cart and the 49.52% customers completed there purchase. However the business is losing half of the customers at checkout stage, highlighting a major opportunity to improve conversion.

- Cart status by Loyalty_Program_Members: Non-Loyal Members has 3,225 customers that completed their purchase, which is slightly higher than the number who abandoned.3,179 customers abandoned their carts. Loyal Members has 3,407 customers that abandoned their carts.3,235 customers completed their purchase.
Insight:Loyal members show more abandonments than purchase completion.

- Cart status by customer segment: This chart compares cart abandonment and purchase completion across four customer segments: New, Regular, Occasional, and VIP. All the customer segments has nearly equal percentages of abandoned cart and purchased completion. New & Regular customers has a slightly higher purchase completion rate while Occasional & Vip has a higher abandoned cart rate.

<img width="1111" height="626" alt="Screenshot 2025-11-20 204406" src="https://github.com/user-attachments/assets/7448051b-3f27-4f66-a3e3-da04683a8bc1" />

4. Transaction Analysis 
- Payment gateway by Transaction status: This chart shows how each payment gateway (Square, Stripe, Amazon Pay, PayPal) performs across four transaction statuses: Cancelled, Completed, Pending, and Refunded.
- Pending : 27.4% of customers using square & 27.38% of customers using stripe has the highest count of pending transaction status 
- Completed: 24.77% of customers using square & 24.88% of customers using amazon pay has the highest count of completed transaction status 
- Cancelled: 25.35% of customers using Amazon pay & 25.94% of customers using PayPal has the highest count of cancelled transaction status 
- Refunded: 25.49% of customers using stripe & 25.17% of customers using PayPal has the highest count of refunded transaction status

- Risk Transaction rate by Payment Method: This table calculates the risk level of each payment method based on cancellation, refund and pending patterns.
 All payment methods show risk levels between 74% and 76%, meaning high risk exposure across all options, Credit card has the lowest risk rate among the methods but only by a small margin.
 Cryptocurrency, PayPal, Bank Transfer shows a slightly higher risk rate.

- Payment method by Transaction status: The chart highlights which payment methods have the highest counts across each transaction status:
  - Pending: Most delays occur with PayPal and Bank Transfer, indicating that customers often pause or wait for confirmation when using these methods.
	- Cancelled: Crypto and Bank Transfer record the highest cancellation counts, suggesting friction or trust issues at the point of payment.
	- Completed: Credit Card and Bank Transfer drive the highest number of successful transactions, showing that customers are most comfortable completing payments through these channels.
	- Refunded: Refunds are most common with PayPal and Bank Transfer, which may signal customer disputes, errors, or product-related concerns linked to these methods.

<img width="1091" height="656" alt="Screenshot 2025-11-20 204501" src="https://github.com/user-attachments/assets/12364e9c-a2d5-4062-a26b-af0dbcda365d" />

### Recommendations
  - Fix the mobile checkout because most customers drop off there.
	- Encourage card payments since they lead to the most successful transactions.
	- Review PayPal and bank transfer issues because they cause delays and cancellations.
	- Focus more marketing on female buyers because they shop and spend the most.
	- Promote the right products to the right ages since each age group prefers different items.
	- Rework low-performing products like shorts with discounts or bundles to increase sales.
