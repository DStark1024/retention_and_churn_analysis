### **Retention & Churn analysis**  
Simulated example of Retention & Churn Analysis.

**Objective:** Analyze player retention and predict churn.  
**Dataset:** [E-Commerce Customer Churn 2025 – 10K (Kaggle)](https://www.kaggle.com/datasets/mohammadmaaz052/e-commerce-customer-churn-2025-10k)  
**Approach:** Cohort analysis, survival analysis, and churn classification.  
**Metrics:** Retention rate, churn rate, ROC-AUC, Kaplan-Meier curves.  

**The data set includes information about:**  
- customer_id - Unique customer identifier
- signup_date - Date customer joined the platform
- last_purchase_date - Most recent order date
- days_since_last_purchase - Recency (as of Jan 1, 2026)
- account_age_days - How long the customer has been active
- country - Top 10 countries (realistic market shares)
- age - 18–80 years (normal distribution)
- gender - Male / Female / Other
- device_type - Mobile / Desktop / Tablet
- favorite_category - Most frequently purchased category
- total_orders - Lifetime number of orders
- total_spent_usd - Lifetime spending in USD
- avg_order_value - Average order value (AOV)
- is_premium_member - 0 = Regular, 1 = Premium subscriber
- churned - Target → 1 if no purchase in last 90 days
