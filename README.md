# 📊 Marketing Campaign Performance & Customer Segmentation Analysis

## 📌 Project Overview

This project analyzes a marketing campaign dataset to evaluate campaign effectiveness, customer response behavior, and revenue impact.

The objective was to:

* Measure campaign response rate
* Identify high-converting customer segments
* Analyze purchasing behavior
* Determine revenue contribution by responders
* Provide data-driven recommendations to improve future campaigns

The analysis was performed using **Power BI** with DAX-based metrics and customer segmentation techniques.


## 🗂 Dataset Description

The dataset contains customer-level marketing and transaction data, including:

* Demographics (Education, Marital Status, Income, Year_Birth)
* Household Information (Kidhome, Teenhome)
* Campaign Response (Response: 0/1)
* Product Spending (Wines, Meat, Fish, Fruits, Sweets, Gold)
* Purchase Channels (Web, Store, Catalog)
* Web Visits & Recency
* Complaint Indicator

Each row represents one customer.



## 🎯 Key Business Questions

1. What is the overall campaign response rate?
2. Which customer segments respond more frequently?
3. Do responders generate higher revenue?
4. Which product categories drive most revenue?
5. What behavioral factors influence response?


## 📊 Dashboard Structure

### Page 1 — Campaign Overview

* Total Customers
* Total Responders
* Response Rate (%)
* Total Revenue
* Revenue from Responders
* Revenue Distribution by Product Category

### Page 2 — Customer Segmentation

* Response Rate by Education
* Response Rate by Marital Status
* Response Rate by Income Group
* Response Rate by Household Composition

### Page 3 — Behavioral Insights

* Web Visits vs Response
* Channel Preference (Web vs Store Purchases)
* Recency vs Response
* Income vs Spend (Scatter Analysis)


## 📈 Key Insights

* High-income customers show significantly higher response rates.
* Customers with higher historical spending are more likely to accept campaigns.
* Wine and Meat categories contribute the largest share of total revenue.
* Web-active customers demonstrate stronger engagement and campaign response.
* Recency plays a role in campaign effectiveness.


## 💡 Business Recommendations

* Target high-income, high-spending customers for premium campaigns.
* Personalize campaigns based on purchase history.
* Increase focus on web-based marketing for digitally active users.
* Develop category-specific promotions for high-revenue products.
* Re-engage customers with low recency using targeted offers.



## 🛠 Tools Used

* Power BI
* DAX (Data Analysis Expressions)
* Data Modeling
* Customer Segmentation
* Business KPI Design



## 📂 Repository Contents

* `Marketing_Campaign_Analysis.pbix` — Power BI dashboard file
* `marketing_campaign.csv` — Dataset
* `README.md` — Project documentation
* `dashboard_screenshots/` — Dashboard visuals



## 🚀 Future Improvements

* Build a predictive response model (Logistic Regression)
* Create customer lifetime value (CLV) segmentation
* Deploy dashboard to Power BI Service
* Integrate campaign ROI calculation




