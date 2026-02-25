**🛍️ Customer Shopping Behavior Analysis**

<img width="1348" height="736" alt="Screenshot 2026-02-25 184150" src="https://github.com/user-attachments/assets/21e1f79b-3559-410e-8d88-019b50c4a566" />

A complete end-to-end Data Analytics Project that analyzes customer shopping behavior using Python, SQL, and Power BI to generate meaningful business insights.

📌 Project Objective

The main goal of this project is to analyze customer purchasing behavior and discover insights related to:

Customer spending patterns

Product popularity

Discount impact on purchases

Customer loyalty

Subscription influence on revenue

These insights help businesses optimize marketing strategies and increase revenue.

📊 Dataset Overview
Feature	Description
Total Records	3,900
Total Columns	18
Dataset Type	Customer Shopping Transactions
Key Dataset Attributes

Customer Information

Age

Gender

Location

Subscription Status

Purchase Details

Item Purchased

Category

Purchase Amount

Season

Size

Color

Shopping Behavior

Discount Applied

Promo Code Used

Previous Purchases

Purchase Frequency

Review Rating

Shipping Type

Missing values were detected in the Review Rating column and handled during preprocessing.

🧹 Data Cleaning & Preprocessing (Python)

Python was used for data preparation and transformation.

Steps Performed

✔ Data loading using pandas

✔ Data exploration using

df.info()
df.describe()

✔ Missing value treatment for Review Rating

✔ Column standardization to snake_case

✔ Feature Engineering

New features created:

age_group
purchase_frequency_days

✔ Removed redundant column

promo_code_used

✔ Loaded cleaned data into PostgreSQL database for SQL analysis.

🗄️ SQL Business Analysis

SQL queries were used to extract important insights.

Business Questions Answered

1️⃣ Revenue comparison by Gender

2️⃣ Customers who used Discount but spent above average

3️⃣ Top 5 products with highest ratings

4️⃣ Shipping Type vs Purchase Amount

5️⃣ Subscribers vs Non-Subscribers Revenue

6️⃣ Products with highest Discount Dependency

7️⃣ Customer Segmentation

New

Returning

Loyal

8️⃣ Top 3 Products per Category

9️⃣ Repeat buyers with Subscription correlation

🔟 Revenue contribution by Age Group

📊 Power BI Dashboard

An interactive Power BI dashboard was built to visualize insights.

Dashboard Includes

📈 Total Revenue Analysis
📊 Customer Segmentation
🛍 Product Category Performance
🚚 Shipping Type Comparison
🎯 Revenue by Age Group

The dashboard helps stakeholders quickly identify trends and patterns.

📂 Project Structure
Customer-Shopping-Behavior-Analysis
│
├── dataset
│   └── customer_shopping_data.csv
│
├── python_analysis
│   └── data_cleaning.ipynb
│
├── sql_queries
│   └── analysis_queries.sql
│
├── powerbi_dashboard
│   └── dashboard.pbix
│
└── README.md
💡 Key Business Insights

✔ Loyal customers generate the highest revenue.

✔ Discount campaigns increase sales but reduce margins.

✔ Subscribers show higher average spending.

✔ Certain products are heavily discount-dependent.

✔ Middle-aged customers contribute the largest revenue share.

🚀 Business Recommendations

🔹 Promote Subscription Programs

🔹 Create Customer Loyalty Rewards

🔹 Optimize Discount Strategy

🔹 Highlight Top Rated Products in Marketing

🔹 Focus marketing on high-value age groups

🛠️ Tools & Technologies
Tool	Purpose
Python	Data Cleaning
Pandas	Data Manipulation
PostgreSQL	SQL Analysis
Power BI	Dashboard Visualization

👨‍💻 Author

**Shashikant Upadhayay**

Aspiring Data Analyst

Connect with me on

LinkedIn
🔗 https://www.linkedin.com/in/shashikant-upadhayay/

⭐ If you like this project, please give it a star on GitHub.
