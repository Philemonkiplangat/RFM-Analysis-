# RFM-Analysis-
### This project involves RFM analysis and developing customer segments based on their RFM scores. The analysis provides insights into customer behaviour and identification of high-value customers, at-risk customers, and potential opportunities for personalized marketing campaigns.
The main steps followed in the analysis involved:
- Uploading the dataset using the required libraries.
- Understand the Dataset:
  Recency (R): The last time a customer made a purchase.
Frequency (F): How often a customer makes a purchase within a specific period.
Monetary (M): The total amount of money a customer has spent.
-  Data Preprocessing:
Clean the Data: Handle missing values, outliers, and inconsistencies in the dataset.
Calculate RFM Values: Calculate R, F, and M values for each customer based on the transaction data.
-RFM Calculation:
Recency (R): Calculate the number of days since the customer's last purchase.
Frequency (F): Count the number of purchases made by each customer.
Monetary (M): Calculate the total amount spent by each customer.
- RFM Score Calculation:
Quartile Analysis: Divide R, F, and M values into quartiles to assign scores from 1 to 4.
RFM Score: Combine the individual R, F, and M scores to create a 3-digit RFM score for each customer.
-Customer Segmentation:
Segment Definition: Define segments based on RFM scores ( High-Value, At-Risk, Low-Value).
Segment Interpretation: Understand the characteristics and behavior of each segment.
- Insights and Opportunities:
High-Value Customers: Identify customers with high R, F, and M scores. They are your most valuable customers.
At-Risk Customers: Look for customers with a high recency score (e.g., 1) but lower frequency and monetary scores. These customers are at risk of churn.
Low-Value Customers: Identify customers with low R, F, and M scores. They might be occasional buyers with low spending potential.
Opportunities: Explore segments with high frequency but low monetary value. These customers might respond well to upselling or cross-selling strategies.
