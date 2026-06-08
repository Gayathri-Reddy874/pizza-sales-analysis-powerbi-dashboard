# 🍕 Pizza Sales Analytics | SQL, Python & Power BI

## 📌 Project Overview

This project presents an end-to-end Pizza Sales Analytics solution built using SQL, Python, and Power BI to analyze sales performance, customer purchasing behavior, product popularity, and revenue trends.

The objective was to transform raw transactional sales data into actionable business insights through data cleaning, exploratory data analysis (EDA), KPI development, and interactive business intelligence dashboards.

The project demonstrates the complete analytics lifecycle:

* Data extraction and business analysis using SQL
* Data cleaning and exploratory analysis using Python
* KPI development using DAX
* Interactive dashboard creation using Power BI
* Business recommendation generation through data-driven insights

### Key Highlights

* Analyzed 21K+ customer orders and 50K+ pizzas sold
* Generated insights from $817K+ total revenue
* Built SQL queries to answer business-critical questions
* Performed exploratory data analysis using Python and Pandas
* Developed interactive Power BI dashboards with DAX measures
* Identified top-performing and underperforming products
* Generated actionable recommendations for sales and inventory optimization

---

# 🎯 Business Problem

Pizza restaurants generate large volumes of transactional data every day, including customer orders, product information, quantities sold, and revenue records.

Without structured analytics, businesses struggle to identify customer preferences, sales trends, product performance, and revenue opportunities.

This project addresses key business questions such as:

* Which pizzas generate the highest revenue?
* Which products receive the highest number of orders?
* What pizza categories are most popular?
* Which pizza sizes contribute the most revenue?
* During which days and months do sales peak?
* Which products require optimization or promotional support?

The goal is to enable data-driven decision-making that improves profitability, customer satisfaction, and operational efficiency.

---

# 🔄 Analytics Workflow

### 1. SQL Business Analysis

Performed SQL-based analysis to:

* Calculate sales KPIs
* Analyze revenue trends
* Identify top and bottom-performing products
* Measure category-wise sales performance
* Evaluate customer ordering behavior

### 2. Python Exploratory Data Analysis (EDA)

Used Python, Pandas, Matplotlib, and Seaborn to:

* Clean and preprocess sales data
* Explore sales distributions and trends
* Validate KPI calculations
* Identify business patterns and anomalies
* Generate supporting visual analytics

### 3. Power BI Dashboard Development

Built interactive dashboards using:

* Power BI
* Power Query
* DAX Measures
* Data Modeling

to provide executive-level business insights.

---

# 📊 Dashboard Preview

### Home Dashboard

![alt text](<Home Dashboard.png>)

### Best & Worst Sellers Dashboard

![alt text](<Best Worst Sellers Dashboard.png>)

---

# 🛠️ Tools & Technologies Used

| Tool        | Purpose                      |
| ----------- | ---------------------------- |
| SQL         | Business Analysis & Querying |
| Python      | Data Cleaning & Analysis     |
| Pandas      | Data Manipulation            |
| Matplotlib  | Data Visualization           |
| Seaborn     | Exploratory Analysis         |
| Power BI    | Dashboard Development        |
| Power Query | Data Transformation          |
| DAX         | KPI Development              |
| CSV         | Dataset Source               |

---

# 📂 Dataset Information

The dataset contains detailed pizza sales transaction records including:

* Order ID
* Order Date
* Order Time
* Pizza Name
* Pizza Category
* Pizza Size
* Quantity
* Unit Price
* Total Price

---

# 📈 Key Performance Indicators (KPIs)

| KPI                      | Value    |
| ------------------------ | -------- |
| Total Revenue            | $817.86K |
| Average Order Value      | $38.31   |
| Total Pizzas Sold        | 50K      |
| Total Orders             | 21K      |
| Average Pizzas Per Order | 2.32     |

### Sample DAX Measures

```DAX
Total Revenue =
SUM(pizza_sales[total_price])

Average Order Value =
DIVIDE([Total Revenue],[Total Orders])

Total Orders =
DISTINCTCOUNT(pizza_sales[order_id])
```

---

# 📊 Dashboard Insights

## Sales Trends

* Friday and Saturday generate the highest number of orders.
* July and January are peak-performing months.
* Weekend demand significantly exceeds weekday demand.

## Category Performance

* Classic pizzas generate the highest sales volume.
* Classic category contributes the largest share of revenue.

## Size Performance

* Large pizzas account for the highest percentage of sales revenue.
* Medium and Large sizes dominate customer preferences.

## Best Sellers

### Revenue Leader

🥇 Thai Chicken Pizza

### Quantity Sold Leader

🥇 Classic Deluxe Pizza

### Order Volume Leader

🥇 Classic Deluxe Pizza

## Underperforming Products

### Lowest Revenue

❌ Brie Carre Pizza

### Lowest Quantity Sold

❌ Brie Carre Pizza

### Lowest Order Volume

❌ Brie Carre Pizza

---

# 🔍 Key Business Insights

### Customer Behavior

* Customers purchase more pizzas during weekends.
* Evening hours generate the highest sales activity.
* Average order contains more than two pizzas.

### Revenue Insights

* Total sales revenue exceeded $817K.
* Average customer spending is approximately $38 per order.

### Product Insights

* Classic pizzas are customer favorites.
* Large pizzas drive significant revenue contribution.
* Certain specialty pizzas show consistently low demand.

---

# 📌 Business Recommendations

### Increase Weekend Promotions

* Launch Friday and Saturday special offers.
* Introduce family and combo meal discounts.

### Expand High-Performing Products

* Introduce new variants within the Classic category.
* Promote Large-size pizzas through bundled offers.

### Improve Low-Performing Products

* Reassess pricing strategies.
* Enhance product visibility through marketing campaigns.
* Optimize recipes based on customer feedback.

### Inventory Optimization

* Increase stock levels for top-selling ingredients.
* Reduce procurement for low-demand products.
* Improve demand forecasting using historical sales trends.

---

# 📁 Repository Structure

```text
Pizza-Sales-Analytics/
│
├── pizza_sales.csv
├── pizza_sales_EDA.ipynb
├── Pizza_sales_analysis.sql
├── Pizza_Sales_Dashboard.py
├── Pizza_Sales_Analysis.pbix
├── Home Dashboard.png
├── Best Worst Sellers Dashboard.png
└── README.md
```

---

# 🚀 How to Use

### Clone Repository

```bash
git clone https://github.com/Gayathri-Reddy874/pizza-sales-analysis-dashboard.git
```

### Open Power BI Dashboard

* Open `Pizza_Sales_Analysis.pbix`
* Refresh data if required
* Explore dashboard filters and visualizations

### Run Python Analysis

```bash
pip install pandas matplotlib seaborn
python Pizza_Sales_Dashboard.py
```

### Execute SQL Analysis

Run queries from:

```text
Pizza_sales_analysis.sql
```

using MySQL, SQL Server, PostgreSQL, or any compatible SQL environment.

---

# 💼 Skills Demonstrated

* SQL
* Python
* Pandas
* Exploratory Data Analysis (EDA)
* Business Intelligence
* Power BI
* Power Query
* DAX
* Data Modeling
* Data Visualization
* KPI Development
* Sales Analytics
* Business Analytics
* Storytelling with Data

---

# 🎓 Project Outcome

Successfully developed an end-to-end sales analytics solution that combines SQL analysis, Python-based exploratory data analysis, and Power BI dashboarding to uncover actionable business insights.

The project enables stakeholders to monitor sales performance, understand customer behavior, optimize inventory planning, evaluate product performance, and make informed business decisions through data-driven analytics.

---

## 👨‍💻 Author

**Mallareddygari Gayathri**

Data Analyst | AI/ML Engineer | Data Scientist 

⭐ If you found this project useful, consider giving it a star!
