# 🍕 Pizza Sales Analysis using SQL

## 📌 Introduction

This project focuses on analyzing pizza sales data using **SQL** to uncover insights into sales performance, customer preferences, and operational efficiency. The goal is to support data-driven decisions to boost revenue and streamline operations.

---

## 🧾 Dataset Overview

The dataset includes several relational tables with the following key components:

- **Pizzas** – Information on pizza sizes, names, and prices  
- **Pizza Types** – Descriptions, categories, and ingredients of each pizza  
- **Orders** – Records of orders placed by customers  
- **Order Details** – Line items for each order including pizza type and quantity  

---

## 🧠 Process & Methodology

The SQL analysis is structured into key categories:

### 🔧 Data Cleaning
- Removed duplicates and nulls
- Standardized date/time formats and pizza naming inconsistencies

### 📊 Exploratory Analysis
- Identified data distributions and basic trends  
- Analyzed order frequency and pizza availability  

### 💰 Sales Analysis
- Total revenue by pizza type, size, and time period  
- Top-selling and highest-revenue pizzas  
- Seasonal and weekly sales trends  

### 👥 Customer Analysis
- Ordering frequency by customer  
- Popular combinations and ordering habits  
- Time-based ordering behavior  

### ⚙️ Operational Analysis
- Order volume by day/hour  
- Kitchen workload patterns  
- Inventory and supply chain insights  

---

## 🗂️ Schema Design

The data schema was designed and visualized using **Power BI**, enabling better understanding of table relationships and query logic.

[Orders]──< [Order Details] >──[Pizzas]──< [Pizza Types]


---

## 📈 Key Insights & Results

1. **Most Ordered & Highest Revenue Pizza:** Identified top-performing pizza types by volume and revenue  
2. **Revenue Trends:** Analyzed daily and monthly revenue patterns to uncover peak times  
3. **Customer Preferences:** Adults prefer large pizzas; weekends show higher sales volume  
4. **Operational Efficiency:** Bottlenecks observed during lunch and weekend hours — opportunity to optimize staff scheduling  

---

## 🚀 Conclusion

This analysis highlights customer trends, operational bottlenecks, and top-performing products. Insights from this project can be used to:
- Optimize **menu offerings**  
- Improve **inventory management**  
- Adjust **staffing based on demand patterns**  
- Drive **strategic marketing** to boost sales

---

## 🛠️ Tools Used

- **SQL** (MySQL / PostgreSQL) – for all data queries and analysis  
- **Power BI** – for schema design and visual exploration  
- **Excel** – for minor data formatting and previewing results  
---

## 🙌 Acknowledgements

Inspired by real-world business challenges in the food service industry. Dataset adapted from practice project materials.
