
# Retail Sales Intelligence & Profit Optimization System

## 🎯 Objective
To analyze retail sales performance and optimize profitability by identifying key business drivers such as sales trends, discount impact, and product-level profitability using SQL, Python, and Power BI.

---

## 🏢 Business Problem
Retail companies often face:
- High sales but low profit
- Excessive discounting
- Unprofitable product categories
- Poor regional performance visibility

This project solves these issues using data-driven insights.

---

## 🛠 Tech Stack
- SQL (Data extraction, cleaning, KPI generation)
- Python (Pandas, NumPy, EDA)
- Power BI (Interactive dashboard)
- Excel (Optional preprocessing)

---

## 📊 Dataset
Superstore Retail Dataset including:
- Sales
- Profit
- Quantity
- Discount
- Category & Sub-Category
- Region
- Customer Segment

## 📓 Interactive Notebook (HTML Version)

👉 [View Analysis Report](notebooks/retail_analysis.html)

This notebook includes:
- Data cleaning and preprocessing  
- KPI calculations  
- Exploratory Data Analysis (EDA)  
- Visualizations and business insights  

---

## 🔑 Key Features

### 📌 Sales Performance Analysis
- Monthly and yearly sales trends
- Revenue growth tracking

### 📌 Profitability Analysis
- Profit margin calculation
- Loss-making product detection

### 📌 Discount Impact Analysis
- Relationship between discount and profit
- Identification of over-discounted products

### 📌 Regional Performance
- Sales and profit by region
- High vs low-performing regions

### 📌 Product Analysis
- Top and bottom performing products
- Category-level insights

---

## 📈 Key Insights (Data-Driven Findings)

### 📊 Monthly Sales vs Profit Trend
<img width="1012" height="486" alt="Monthly Sales and Profit Trend" src="https://github.com/user-attachments/assets/3e816d9b-d0fe-4086-a150-ef2fc929a187" />

- Sales fluctuate across months due to seasonality
- Profit does not always follow sales trend
- Some high-sales months show reduced profitability due to discounts

---

### 📉 Discount vs Profit Relationship
<img width="716" height="468" alt="Discount vs Profit Relationship" src="https://github.com/user-attachments/assets/7de292b8-c2ce-44d8-87d2-dbc496f9253f" />

- Higher discounts strongly reduce profit
- Many transactions operate at low or negative margins
- Discounting strategy needs optimization

---

### 🌍 Regional Performance Analysis
<img width="566" height="433" alt="Regional Performance Heatmap" src="https://github.com/user-attachments/assets/0acfecff-0f7a-40ce-88ac-3127f044e3b6" />

- Some regions generate high revenue but low profit
- Performance varies significantly across geography
- Indicates inefficient regional strategy allocation

---

### 📦 Category Performance Analysis
<img width="578" height="543" alt="Sales by Catergory" src="https://github.com/user-attachments/assets/096f3482-3165-4381-bc2f-9616db473fd3" />
- Revenue is concentrated in a few categories
- Some high-sales categories are less profitable
- Portfolio optimization is required

### 📦 Sub-Category Performance Analysis
<img src="images/subcategory_sales.png" width="700"/>
- Sales are unevenly distributed across sub-categories  
- A small number of sub-categories contribute majority of revenue  
- Several sub-categories show weak performance 

👉 Insight: Revenue is highly concentrated in few sub-categories, creating dependency risk.

## 📊 Power BI Dashboard
Includes:
- KPI Cards (Sales, Profit, Margin)
- Trend Analysis (Monthly Sales/Profit)
- Region Heatmap
- Category Breakdown
- Discount vs Profit Scatter Plot

---
## 💼 Business Impact
This system helps businesses:
- Optimize pricing strategy
- Reduce unnecessary discounting
- Improve profit margins
- Identify weak product categories
- Improve regional strategy decisions

---
---

🚀 How to Run This Project
1️⃣ Clone the repository
git clone https://github.com/Laxmi0412/Retail-sales-intelligence-system.git
2️⃣ Navigate to project folder
cd Retail-sales-intelligence-system
3️⃣ Install dependencies
pip install -r requirements.txt
4️⃣ Launch Jupyter Notebook
jupyter notebook notebooks/retail_analysis.ipynb

