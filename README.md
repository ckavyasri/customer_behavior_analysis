# 👨🏻‍💻 Customer Shopping Behavior Analysis
# 📌 Project Overview
This project focuses on analyzing customer shopping behavior using real transactional data. The goal is to understand how customers purchase products, what influences their spending, and how businesses can improve sales and customer engagement using data-driven insights. The project encompasses all critical stages of data analysis, from data preparation and modeling to insight generation, visualization, and reporting.
# 🎯 Business Problem
A retail company wants to understand changing customer purchasing patterns across demographics, product categories, discounts, and subscriptions.
The key question addressed in this project is:
How can customer shopping data be used to identify trends, improve engagement, and optimize marketing and product strategies?
# 📂 Dataset Information
Rows: 3,900

Columns: 18

Key Features:

Customer details: Age, Gender, Location, Subscription Status

Purchase details: Item Purchased, Category, Amount, Season, Size, Color

Behavior data: Discounts, Purchase Frequency, Reviews, Shipping Type

Missing Values: Review Rating column (handled during data cleaning)

# 🛠️ Tools & Technologies Used
Python – Data cleaning, EDA, feature engineering

PostgreSQL (SQL) – Business queries and analysis

Power BI – Interactive dashboard and visualizations

# 🔍 Project Workflow
1. Understanding the Business Problem
   Reviewed the business objectives and defined key questions related to customer behavior, spending patterns, and loyalty.
2. Data Collection & Understanding
   Used a transactional dataset containing customer demographics, purchase details, and shopping behavior.
3. Data Cleaning & Preparation (Python)
   - Handled missing values in review ratings.
   - Standardized column names for consistency.
   - Removed redundant columns.
   - Created new features such as age groups and purchase frequency.
4. Exploratory Data Analysis (EDA)
   - Analyzed customer demographics and purchase trends.
   - Studied spending behavior across categories, seasons, and shipping types.
   - Identified patterns using summary statistics and visualizations.
5. Database Integration
   - Loaded the cleaned dataset into PostgreSQL.
   - Structured data to simulate real business transactions.
6. Data Analysis (SQL)
   - Performed revenue analysis by gender and age group.
   - Compared subscribers vs non-subscribers.
   - Identified high-spending discount users.
   - Segmented customers into New, Returning, and Loyal groups.
   - Analyzed top products and categories.
7. Data Visualization (Power BI)
   - Built an interactive dashboard.
   - Visualized revenue, subscriptions, ratings, and category-wise sales.
   - Enabled easy filtering for business insights.
8. Insights & Business Recommendations
   - Interpreted results to provide actionable recommendations.
   - Suggested strategies for improving customer retention, subscriptions, and marketing effectiveness.
9. Documentation & GitHub Deployment
   - Organized Python scripts, SQL queries, and dashboard files.
   - Created a clean README for project explanation and presentation.
# 📊 Key Insights
- Loyal customers contribute the majority of purchases.
- Express shipping users show slightly higher average spend.
- Some products are highly discount-dependent.
- Young adults and middle-aged customers generate higher revenue.
- Subscriptions show potential for improved customer retention.
# 💡 Business Recommendations
- Improve subscription offerings to boost long-term loyalty
- Reward repeat customers to increase retention
- Optimize discount strategies to balance revenue and margins
- Focus marketing on high-performing products and age groups
# ✅ Conclusion
In this project, customer shopping data was analyzed to understand buying patterns, customer preferences, and spending behavior. Using Python, SQL, and Power BI, meaningful insights were generated to support better business decisions. This project helped me gain hands-on experience in data cleaning, analysis, and visualization, and shows how data can be used to improve customer engagement and sales.

