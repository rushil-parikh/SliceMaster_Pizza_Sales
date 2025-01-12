# SliceMasters Pizza Sales Analysis

![image](https://github.com/user-attachments/assets/2b593bb8-1694-40b1-a859-992193a14e14)


## Project Objective
The objective of this project was to analyze SliceMasters' pizza sales data to uncover trends, identify top-performing products, and evaluate key performance indicators (KPIs). By leveraging Zeppelin Spark, which utilizes a mix of SQL and HQL, I aimed to provide actionable insights that could drive business decisions for revenue growth and operational efficiency.

---

## Dataset Description
The dataset used for this project contains transactional data from SliceMasters' pizza sales. Key attributes include:

- **Order Details**: `order_id`, `order_date`
- **Pizza Information**: `pizza_name`, `pizza_category`, `pizza_size`
- **Sales Metrics**: `quantity`, `total_price`

This dataset captures the details necessary for analyzing sales performance across multiple dimensions such as time, product categories, and sizes.

---

## Analysis Questions
I focused on answering the following business questions:

1. **KPIs**:
   - What is the total revenue from pizza sales?
   - What is the average order value?
   - How many pizzas were sold in total?
   - How many orders were received?
   - What is the average number of pizzas per order?

2. **Trend Analysis**:
   - What are the daily and monthly patterns in order volumes?

3. **Sales by Category and Size**:
   - What percentage of sales comes from each pizza category?
   - Which pizza sizes are the most popular?

4. **Product Performance**:
   - Which are the top 5 and bottom 5 pizzas by revenue and quantity?
   - What are the most and least ordered pizzas?

---

## Methodology
### 1. Zeppelin Spark Queries
To extract and analyze the data, I wrote queries that:

- Aggregated sales data to calculate metrics like total revenue, average order value, and total orders.
- Grouped data by categories (e.g., pizza size or category) to identify trends and popular products.
- Used ranking and filtering techniques to highlight top-performing and underperforming items.

### 2. Trend Analysis
- Identified daily and monthly patterns in order volumes to uncover high-demand periods.

### 3. Product-Level Analysis
- Evaluated product popularity and performance based on total revenue, quantity sold, and order frequency.

---

## Key Insights
### KPIs:
- **Total Revenue**: The total revenue from pizza sales was calculated to be approximately $817,860.05.
- **Average Order Value**: The average value of a pizza order is about $38.31, suggesting that customers are spending this amount on average per order.
- **Total Pizzas Sold**: Around 49,574 pizzas were sold in the last quarter.
- **Total Orders**: There were a total of 21,350 orders received in the last quarter.
- **Average Pizzas Per Order**: On average, about 2.32 pizzas were sold per order.

### Sales Trends:
- **Daily Trends**: Orders were analyzed by day of the week, with Friday having the highest number of orders at 3,538 and Sunday the lowest at 2,624.
- **Monthly Trends**: Order trends were analyzed by month, with July having the highest number of orders at 1,935 and October the lowest at 1,646.

### Product Performance:
- **Top Performers**:
  - The "Thai Chicken Pizza" was the top-selling pizza by revenue, earning around $43,434.25.
- **Underperformers**:
  - Highlighted pizzas with low sales, potentially due to low demand or pricing issues.

### Sales by Category and Size:
- **Category Sales**: The "Classic" category contributed approximately 26.91% of total revenue, followed by "Supreme" at about 25.46%.
- **Pizza Size Sales**: Large-sized pizzas contributed to 45.89% of the total revenue, the largest share among all sizes.

---

## Conclusion
This project provides actionable insights into SliceMasters’ sales performance. Key recommendations include:

1. Focus on high-performing pizzas like "Thai Chicken Pizza" and optimize inventory to meet their demand.
2. Reassess pricing and marketing strategies for underperforming pizzas.
3. Leverage sales trends to align promotions and staffing during peak periods.

By using Zeppelin Spark and its SQL/HQL capabilities to analyze real-world data, I demonstrated how data-driven strategies can optimize business operations and drive revenue growth.

---

