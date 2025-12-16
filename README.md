📌 Project Overview

This project analyzes customer shopping behavior using transactional data to uncover patterns that help improve sales, customer engagement, and long-term loyalty.
The analysis combines Python, SQL, and Power BI to deliver actionable, business-ready insights.

The dataset includes 3,900 customer purchases across multiple demographics, product categories, locations, and purchase behaviors.

📊 Dataset Summary

* Total Transactions: 3,900
* Features per Transaction: 18
* Product Categories: 4
* Customer Locations: 50

The dataset covers:
* Customer demographics (age, gender)
* Purchase behavior
* Discounts & subscriptions
* Reviews & satisfaction
* Loyalty and repeat purchases

🧰 Tech Stack

* Python: Pandas, NumPy, Matplotlib, Seaborn
* SQL: PostgreSQL (CTEs, aggregations, window functions)
* Power BI: Interactive dashboards & DAX measures
* Jupyter Notebook: Exploratory data analysis
* Git & GitHub: Version control and project hosting

🔄 Project Workflow
1️⃣ Data Preparation & Cleaning (Python)

* Loaded raw dataset using Pandas
* Handled missing values (37 missing review ratings imputed using median)
* Standardized column names (snake_case)

Created new features:
* Age groups
* Purchase frequency
* Customer loyalty categories
* Prepared cleaned data for database ingestion

2️⃣ Data Analysis (SQL)

* Designed structured tables in PostgreSQL
* Wrote optimized SQL queries to analyze:
* Customer loyalty & segmentation
* Subscription behavior
* Discount impact on revenue
* Gender-wise and age-wise revenue trends
* Used CTEs and aggregations for clarity and performance

3️⃣ Visualization & Insights (Power BI)

* Built an interactive dashboard covering:
* Revenue by Gender
* Male customers contribute ~68% of total revenue
* Customer Segmentation
* ~80% of customers are loyal buyers
* Subscription Analysis
* 27% subscription rate
* Repeat buyers show higher subscription adoption
* Top Products by Rating
* Gloves, Sandals, Boots lead customer satisfaction
* Discount Impact
* Discounts increase volume without reducing high-value spending
* Revenue by Age Group
* Young adults lead revenue, with balanced contribution across segments

📈 Key Business Insights

* Loyal customers are the backbone of revenue growth
* Male customers currently dominate spending → opportunity to grow female engagement
* Repeat buyers are ideal targets for subscription conversion
* Discounts can be strategically used without harming profitability
* High-rated products should be emphasized in marketing campaigns

💡 Strategic Recommendations

* Boost Subscriptions: Target loyal and repeat customers with exclusive benefits
* Strengthen Loyalty Programs: Reward frequent buyers
* Optimize Discounts: Balance promotions with margin protection
* Product Positioning: Highlight top-rated products
* Targeted Marketing: Focus on high-revenue age groups and express shipping users
