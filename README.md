# Credit-card-Usage-analysis
Insights and Outcomes

The dataset includes 100 unique customers spanning different cities, products (Gold, Silver, Platinum), and segments (e.g., Salaried, Self-Employed).
Customers aged below 18 were adjusted to the mean age (revised to ~43 years).
Spending and Repayment:

Monthly spend averages ranged from ₹79,642 (Nov 2004) to ₹213,863 (Aug 2006).
Monthly repayment averages varied, with the highest repayment of ₹204,422 (Jan 2006).
Profit Analysis for Bank:

Monthly profit (repayment - spend) was positive for some months, with the highest profit being ₹94,703 (Dec 2005).
Profits from interest (at 2.9% monthly) peaked at ₹2,746 (Dec 2005).
Top Product Types:

High-spending categories included Petro, Camera, Food, Air Ticket, and Train Ticket.
City Insights:

Cochin had the maximum total spend across cities, dominating other cities in expenditure.
Age Group Spending:

The 41-50 age group contributed the highest spending, showcasing mid-life financial activity as a key driver.
Top Customers by Repayment:

The top customer (A61) repaid ₹10.5M, followed by A60 (₹9.8M) and A13 (₹9.5M).
Approach in Detail
Data Cleaning and Preprocessing:

Adjusted outliers by capping spend amounts at 50% of the credit limit and repayment amounts at the credit limit.
Ensured uniformity by converting date formats and handling missing values.
Customer Segmentation:

Grouped customers by demographics (city, product type, age group) to analyze behavior patterns.
Spending and Repayment Trends:

Monthly and yearly trends were visualized to identify seasonal spikes and high-spending categories.
Profit Calculation:

Profit was computed as the difference between repayment and spending, and interest (2.9%) was calculated on positive profits.
Top Customer Identification:

Used Python queries to extract the top 10 customers by repayment amount for each city, product type, and time period.
Visualization:

Created bar plots, pie charts, and pivot tables for a clear graphical representation of trends like city-wise spending and monthly product comparisons.
Quantitative Insights
Spend vs. Repayment: On average, customers spent less than their limit but repaid amounts closer to their limit, showing disciplined repayment behavior.
Top Spender Cities: Cochin was the top-spending city, contributing significantly to overall expenditures.
High-Profit Months: Months with high profits (e.g., Dec 2005) indicate effective customer repayments with fewer delinquencies.
Business Impact
Enhanced Marketing Strategies: Identifying top-spending cities and product categories allows targeted promotions.
Customer Profiling: Segmentation by age group and city helps tailor credit limits and rewards.
Profit Maximization: Insights into repayment behaviors enable optimized interest rate strategies.
