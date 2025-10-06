🍕 Pizza Sales Analysis Dashboard
📊 Project Overview

This project analyzes pizza sales data using SQL and Power BI to uncover key insights such as total revenue, best-selling pizza types, and sales trends over time.
The goal of this analysis is to help the business understand customer preferences, optimize inventory, and improve sales strategies through data-driven decision-making.

🗂️ Dataset

The dataset contains four main tables:

orders → Order details such as order ID, date, and time.

order_details → Quantity and pizza IDs for each order.

pizzas → Information about pizza sizes, prices, and pizza type IDs.

pizza_types → Pizza category and name information.

⚙️ Tools & Technologies Used

SQL Server → Data cleaning, transformation, and analysis.

Power BI → Data visualization and dashboard creation.

Excel / CSV → Data storage and import source.

🧠 Key Analyses Performed

✅ Total number of orders placed.
✅ Total revenue generated from pizza sales.
✅ Most common pizza size ordered.
✅ Top 5 most ordered pizza types.
✅ Category-wise distribution of pizzas.
✅ Hourly distribution of orders.
✅ Average number of pizzas ordered per day.
✅ Top 3 pizza types by revenue per category.
✅ Cumulative and running total of revenue over time.

📈 Power BI Dashboard Insights

The interactive dashboard includes:

KPI Cards: Total Revenue, Total Orders, Total Pizzas Sold, Avg Pizzas per Order.

Bar Chart: Top 5 Most Ordered Pizza Types.

Line Chart: Running Total of Revenue by Date.

Pie Chart: Category-wise Revenue Share.

Column Chart: Cumulative Revenue Over Time.

🧩 Data Model

One-to-Many relationship between pizzas → order_details.

One-to-Many relationship between orders → order_details.

One-to-Many relationship between pizza_types → pizzas.

These relationships were created in Power BI’s Model View to connect all tables logically.

🚀 Insights & Conclusion

Classic pizzas contributed the highest revenue.

Large size pizzas were the most popular among customers.

Evening hours saw the highest number of orders.

A few specific pizza types like Barbecue Chicken and Classic Deluxe generated the majority of revenue.

This analysis demonstrates how combining SQL querying with Power BI visualization helps transform raw data into actionable business insights.

💡 Future Improvements

Add customer demographics and location data for deeper insights.

Include time-series forecasting for sales prediction.

Automate data refresh in Power BI using SQL connections.
