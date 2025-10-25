# 🥡 From Data to Delivery: A Foodpanda Excel Dashboard

**An Interactive Excel Dashboard Analyzing Customer Orders, Revenue, and Loyalty Patterns**

This project presents an Excel-based analytics dashboard built using a simulated Foodpanda dataset.  
The dashboard explores customer behavior, restaurant performance, and key operational metrics — all visualized through dynamic pivots, slicers, and charts.

---

## 📊 Dashboard Preview
**Dashboard 1**

![Dashboard Screenshot](https://github.com/Tatheer-Za-ra/Data-analysis-project-FoodPanda-data-set/blob/main/dashboard%201.png)

**Dashboard 2**

![Dashboard Screenshot](https://github.com/Tatheer-Za-ra/Data-analysis-project-FoodPanda-data-set/blob/main/dashboard%202.png)

---

## 🎯 Project Objective
To demonstrate end-to-end data analysis and visualization skills in Excel by transforming raw food delivery data into actionable business insights.  
The focus is on understanding customer retention, order behavior, and operational efficiency through interactive KPIs.

---

## 🔑 Key Performance Indicators (KPIs)

| # | KPI | Insight | Metric |
|---|-----|----------|---------|
| 1 | **Total Revenue** | How much revenue was generated | `SUM(price)` |
| 2 | **Total Orders** | Total number of transactions | `COUNT(order_id)` |
| 3 | **Average Order Value (AOV)** | Average revenue per order | `TotalRevenue / TotalOrders` |
| 4 | **Orders & Revenue by Month (Trend)** | Monthly growth and seasonality | Count of orders, Sum of revenue by month |
| 5 | **Dishes by Revenue** | Which dishes generate the most revenue | Dish name vs. total revenue |
| 6 | **Restaurants by Revenue & Avg Rating** | Identify high-performing restaurants | Restaurant name vs. revenue and rating |
| 7 | **Delivery Success Rate & Failures** | Measure operational reliability | % Delivered vs. Delayed/Cancelled |
| 8 | **Average Rating & Distribution** | Assess customer satisfaction levels | Avg rating by city/restaurant |
| 9 | **Payment Method Split & Revenue per Method** | Understand customer payment preferences | Count and revenue by payment method |
| 10 | **Top Cities by Orders & AOV** | Track high-demand regions | Orders and AOV by city |
| 11 | **Orders by Churned Status** | Active vs inactive customer behavior | Count by churned flag |
| 12 | **Customer Loyalty Points Analysis** | Evaluate loyalty reward effectiveness | Sum(loyalty_points) by customer |

---

## 🧩 Dataset Overview

| Column | Description |
|--------|--------------|
| **customer_id** | Unique identifier for each customer |
| **gender** | Gender of the customer (Male, Female, Other) |
| **age** | Age group of the customer (e.g., Adult, Senior) |
| **city** | City where the customer is located |
| **signup_date** | Date when the customer registered on Foodpanda |
| **order_id** | Unique identifier for each order |
| **order_date** | Date when the order was placed |
| **restaurant_name** | Name of the restaurant from which the order was made |
| **dish_name** | Name of the dish ordered |
| **category** | Category of the food item (e.g., Italian, Dessert) |
| **quantity** | Number of items ordered |
| **price** | Price of the order |
| **payment_method** | Payment option used (Cash, Card, Wallet) |
| **order_frequency** | Total number of orders placed by the customer |
| **last_order_date** | Most recent date of order for the customer |
| **loyalty_points** | Reward points earned by the customer |
| **churned** | Customer activity status (Active or Inactive) |
| **rating** | Rating given by the customer for the order |
| **rating_date** | Date when the rating was submitted |
| **delivery_status** | Final status of the delivery (Delivered, Delayed, Cancelled) |

---

## ⚙️ Tools & Techniques

- **Microsoft Excel**
  - Power Query for data cleaning and transformation  
  - PivotTables and PivotCharts for dynamic analysis  
  - Slicers for interactivity  
  - Conditional Formatting for highlighting insights  

---

## 📈 Insights Highlighted in the Dashboard

- **4.8M Rs Total Revenue** generated from **6,000 orders**
- **Cash** emerged as the most used payment method
- **Subway** led in overall revenue among restaurants
- **Peshawar** showed the **highest AOV**
- **Delivery success rate** dominated with minimal failures
- **Loyalty points** strongly correlated with customer retention

---

## 🚀 How to Use
1. Download the `.xlsx` file from this repository.  
2. Open it in Microsoft Excel (preferably 2019 or 365).  
3. Use slicers (City, Gender, Payment Method, Month, etc.) to interact with the data.  
4. Explore KPIs and visual insights dynamically.

---

## 🧭 Project Workflow
1. **Data Cleaning:** Handled missing values, standardized date formats, and removed duplicates using Power Query.  
2. **Data Modeling:** Built relationships between order and customer data using unique IDs.  
3. **Visualization:** Designed KPI cards, pivot charts, and interactive slicers.  
4. **Storytelling:** Structured the dashboard to follow the flow — Revenue → Customer Behavior → Delivery & Payment Performance.

---

## 💡 Future Enhancements
- Add **RFM segmentation** and **customer lifetime value (CLV)** analysis  
- Build a **Power BI version** for advanced drill-throughs  
- Automate **data refresh** through Power Query connections  

---

## 👩‍💻 Author
**Tatheer Zahra**  
_Aspiring Data Analyst | BI Intern @ AidaDataYard_  
📍 [LinkedIn Profile](www.linkedin.com/in/tatheer-zahra-6a1232289)
