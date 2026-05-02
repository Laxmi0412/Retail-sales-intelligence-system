Retail Sales Intelligence & Profit Optimization System


📌 Overview

This project is an end-to-end retail analytics system designed to evaluate sales performance, profit efficiency, and discount effectiveness. It transforms raw transactional data into actionable business insights to support pricing strategy, product optimization, and regional performance decisions.


🎯 Business Objective

Retail businesses often struggle with:

High revenue but low profitability
Over-reliance on discounting strategies
Poor visibility into regional performance
Unbalanced product category contribution

This system addresses these challenges by identifying what drives profit versus what only drives sales.


🧰 Tech Stack
SQL → Data extraction, aggregation, KPI creation
Python (Pandas, NumPy) → Data cleaning & exploratory analysis
Matplotlib / Seaborn → Data visualization
Power BI → Interactive dashboards & business reporting
Excel → Initial data validation & preprocessing


📊 Dataset Overview

The dataset includes retail transactional data with the following attributes:

Sales (Revenue generated per transaction)
Profit (Net profitability per transaction)
Quantity (Units sold)
Discount (Pricing adjustments applied)
Category & Sub-Category (Product segmentation)
Region & Customer Segment (Market segmentation)

⚙️ Project Workflow
1. Data Preparation
Cleaned missing and inconsistent values
Standardized numerical fields (Sales, Profit, Discount)
Structured dataset for analytical processing


2. KPI Development (SQL + Python)
Total Sales
Total Profit
Profit Margin
Discount Impact Ratio


3. Exploratory Data Analysis (EDA)
Sales vs Profit behavior analysis
Discount impact evaluation
Regional and category-level breakdowns


4. Visualization & Dashboarding (Power BI)
Built interactive dashboards for business users
Enabled drill-down analysis by region, category, and time


📈 Key Insights

📊 1. Sales vs Profit Decoupling

High sales do not consistently translate into high profit. Several high-revenue periods show reduced profitability due to discounting pressure.
<img width="857" height="487" alt="sales vs profit trind" src="https://github.com/user-attachments/assets/3d0ce081-d900-461c-a0cb-f641267fca8d" />


📉 2. Discount Impact on Profitability

Strong negative correlation between discount rate and profit. Excessive discounting leads to margin erosion and inefficient pricing strategies.
<img width="561" height="393" alt="Discount vs profit (Impact on probability)" src="https://github.com/user-attachments/assets/57e86de8-af13-495d-aa8b-e4f467e81288" />


🌍 3. Regional Performance Imbalance

Significant variation in profitability across regions. Some high-sales regions underperform in profit contribution, indicating the need for region-specific strategies.
<img width="644" height="393" alt="profit by region" src="https://github.com/user-attachments/assets/021df560-7b63-457a-bee1-23e343218cdc" />


📦 4. Category Concentration Risk

Revenue is heavily concentrated in a few product categories, while several categories contribute disproportionately low profit.
<img width="566" height="393" alt="profit by catergory" src="https://github.com/user-attachments/assets/f76ac28c-d141-4038-9782-29b420c7c792" />


📦 5. Sub-Category Dependency Risk

A small number of sub-categories drive most revenue, creating dependency risk and reducing portfolio balance.
<img width="860" height="537" alt="profit- sub catergory" src="https://github.com/user-attachments/assets/e7e38f97-4594-4690-8304-6fa15d47d92d" />





📊 Power BI Dashboard Features
KPI Cards (Sales, Profit, Margin)
Monthly Sales & Profit Trends
Regional Performance Heatmap
Category & Sub-Category Breakdown
Discount vs Profit Relationship Analysis


💡 Business Impact

This system helps businesses:

Optimize pricing strategy
Reduce unnecessary discounting
Improve profit margins
Identify underperforming products
Make data-driven regional decisions


📌 Key Recommendations
Reduce discounting in low-margin segments
Focus on high-profit categories
Improve underperforming regions
Diversify product portfolio
Monitor loss-making sub-categories
