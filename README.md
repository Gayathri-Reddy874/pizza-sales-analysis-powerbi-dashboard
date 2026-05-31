# 🍕 Pizza Sales Analysis Dashboard | Power BI

## 📌 Project Overview

The Pizza Sales Analysis Dashboard is a comprehensive Business Intelligence project developed using **Power BI** to analyze pizza sales performance, customer purchasing behavior, product popularity, and revenue trends.

In the highly competitive food and restaurant industry, understanding customer preferences and sales patterns is essential for maximizing revenue and improving operational efficiency. This project leverages historical pizza sales data to provide actionable insights through interactive visualizations and key performance indicators (KPIs).

The dashboard enables stakeholders to:

- Monitor overall business performance.
- Analyze customer ordering patterns.
- Identify best-selling and worst-selling pizzas.
- Understand category and size-wise sales distribution.
- Discover peak sales periods and seasonal trends.
- Make data-driven decisions to improve profitability and inventory planning.

---

## 🎯 Business Problem

Pizza restaurants generate large volumes of transactional data every day, including:

- Order details
- Pizza categories
- Pizza sizes
- Quantities sold
- Revenue generated
- Customer purchasing patterns

Without proper analysis, valuable insights remain hidden within the data.

This project aims to answer critical business questions such as:

- Which pizzas generate the highest revenue?
- Which pizza categories are most popular?
- What pizza sizes do customers prefer?
- During which days and months do sales peak?
- Which products are underperforming?
- How can the business optimize its menu and marketing strategy?

By answering these questions, the business can improve sales performance, optimize inventory management, and enhance customer satisfaction.

---

# 📊 Dashboard Preview

## Home Dashboard

![alt text](<Home Dashboard.png>)

## Best & Worst Sellers Dashboard

![alt text](<Best Worst Sellers Dashboard.png>)

---

# 🛠️ Tools & Technologies Used

| Tool | Purpose |
|--------|----------|
| Power BI | Data Visualization & Dashboard Development |
| Microsoft Excel (CSV) | Dataset Storage |
| DAX | KPI Calculations & Measures |
| Power Query | Data Cleaning & Transformation |
| Data Modeling | Relationship Building |

---

# 📂 Dataset Information

The dataset contains detailed pizza sales transaction records including:

| Column |
|----------|
| Order ID |
| Order Date |
| Order Time |
| Pizza Name |
| Pizza Category |
| Pizza Size |
| Quantity |
| Unit Price |
| Total Price |

---

# 📈 Key Performance Indicators (KPIs)

The following KPIs were developed to evaluate business performance:

## 1. Total Revenue

Measures the total income generated from pizza sales.

**Formula:**

```DAX
Total Revenue = SUM(pizza_sales[total_price])
```

### Result

💰 **817.86K**

---

## 2. Average Order Value

Measures the average amount spent per order.

**Formula:**

```DAX
Average Order Value =
DIVIDE([Total Revenue],[Total Orders])
```

### Result

💰 **38.31**

---

## 3. Total Pizzas Sold

Measures the total quantity of pizzas sold.

**Formula:**

```DAX
Total Pizzas Sold =
SUM(pizza_sales[quantity])
```

### Result

🍕 **50K**

---

## 4. Total Orders

Measures the total number of orders placed.

**Formula:**

```DAX
Total Orders =
DISTINCTCOUNT(pizza_sales[order_id])
```

### Result

🛒 **21K**

---

## 5. Average Pizzas Per Order

Measures the average number of pizzas purchased per order.

**Formula:**

```DAX
Average Pizzas Per Order =
DIVIDE([Total Pizzas Sold],[Total Orders])
```

### Result

🍕 **2.32**

---

# 📊 Dashboard Visualizations

## 1️⃣ Daily Trend for Total Orders

### Visualization

Bar Chart

### Purpose

Displays total orders by day of the week.

### Insight

- Highest orders occur on:
  - Friday
  - Saturday

This indicates increased demand during weekends.

---

## 2️⃣ Monthly Trend for Total Orders

### Visualization

Line Chart

### Purpose

Shows monthly ordering patterns.

### Insight

- Peak months:
  - July
  - January

- Lower sales observed toward the end of the year.

---

## 3️⃣ Percentage of Sales by Pizza Category

### Visualization

Pie Chart

### Purpose

Displays revenue contribution by pizza category.

### Categories

- Classic
- Supreme
- Chicken
- Veggie

### Insight

Classic pizzas generate the highest revenue contribution.

---

## 4️⃣ Percentage of Sales by Pizza Size

### Visualization

Donut Chart

### Purpose

Shows customer preference for pizza sizes.

### Sizes

- S
- M
- L
- XL
- XXL

### Insight

Large-sized pizzas contribute the highest percentage of revenue.

---

## 5️⃣ Total Pizzas Sold by Pizza Category

### Visualization

Funnel Chart

### Purpose

Compares quantity sold across pizza categories.

### Insight

Classic category pizzas have the highest sales volume.

---

## 6️⃣ Top 5 Best Sellers

### Metrics Evaluated

- Revenue
- Quantity Sold
- Total Orders

### Best Seller Insights

#### Revenue

🥇 Thai Chicken Pizza generates the highest revenue.

#### Quantity Sold

🥇 Classic Deluxe Pizza sells the highest quantity.

#### Total Orders

🥇 Classic Deluxe Pizza receives the highest number of orders.

---

## 7️⃣ Bottom 5 Worst Sellers

### Metrics Evaluated

- Revenue
- Quantity Sold
- Total Orders

### Worst Seller Insights

#### Revenue

❌ Brie Carre Pizza generates the lowest revenue.

#### Quantity Sold

❌ Brie Carre Pizza records the lowest quantity sold.

#### Orders

❌ Brie Carre Pizza receives the fewest orders.

---

# 🔍 Key Business Insights

### Customer Behavior

- Customers order more pizzas on weekends.
- Friday evenings and Saturday evenings are peak sales periods.

### Product Performance

- Classic pizzas are the most preferred category.
- Large-sized pizzas contribute the largest share of revenue.

### Revenue Analysis

- Total Revenue exceeds **$817K**.
- Average customer spending per order is approximately **$38**.

### Best Sellers

- Thai Chicken Pizza generates the most revenue.
- Classic Deluxe Pizza dominates in quantity sold and total orders.

### Underperforming Products

- Brie Carre Pizza consistently ranks lowest across all metrics.
- Menu optimization opportunities exist for low-performing products.

---

# 📌 Business Recommendations

### Increase Promotions During Peak Periods

- Run special offers on Fridays and Saturdays.
- Introduce combo deals during evening hours.

### Focus on High-Performing Categories

- Expand Classic pizza offerings.
- Promote Large-size pizzas through bundled deals.

### Improve Underperforming Products

- Reassess pricing strategy for Brie Carre Pizza.
- Improve recipe, marketing, or promotional visibility.

### Inventory Optimization

- Stock more ingredients for top-selling pizzas.
- Reduce wastage by monitoring low-demand products.

### Seasonal Campaign Planning

- Increase marketing efforts before July and January.
- Launch targeted campaigns during high-demand periods.

---

# 📁 Repository Structure

```bash
Pizza-Sales-Analysis/
│
├── pizza_sales.csv 
├── Pizza_Sales_Analysis.pbix
├── Home Dashboard.png
├── Best Worst Sellers Dashboard.png
└── README.md
```

---

# 🚀 How to Use

### Step 1

Clone the repository

```bash
git clone https://github.com/Gayathri-Reddy874/pizza-sales-analysis-powerbi-dashboard.git
```

### Step 2

Open the `.pbix` file in Power BI Desktop.

### Step 3

Connect the dataset if required.

### Step 4

Refresh the dashboard.

### Step 5

Interact with slicers and filters to explore insights.

---

# 💼 Skills Demonstrated

- Data Analysis
- Business Intelligence
- Dashboard Design
- Power BI
- DAX Calculations
- Data Modeling
- Data Visualization
- KPI Development
- Business Insights Generation
- Storytelling with Data

---

# 🎓 Project Outcome

This Power BI dashboard successfully transforms raw pizza sales data into meaningful business insights. It helps stakeholders understand customer preferences, identify sales trends, evaluate product performance, and make informed decisions that can improve revenue, operational efficiency, and customer satisfaction.

---

## 👩‍💻 Author

**Mallareddygari Gayathri**

Aspiring Data Analyst | Data Scientist | AI/ML Engineer


⭐ If you found this project useful, consider giving it a star!
