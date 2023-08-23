
Pizza Sales Analysis - SQL + Excel 📈📊
Analyzing pizza sales data using SQL queries and Excel by exploring key metrics, tracking trends, and identifying top and worst sellers. Ensured data accuracy through validation. Included valuable insights for informed decision-making.

Here's a breakdown of the SQL queries and their purpose:

The Key Performance Indicators (KPIs):
1.Total Revenue: Calculates the sum of the "total_price" column to obtain the total revenue from pizza sales.
2.Average Order Value: Divides the sum of "total_price" by the count of distinct "order_id" values to calculate the average value of each order.
3.Total Pizzas Sold: Calculates the sum of the "quantity" column to determine the total number of pizzas sold.
4.Total Orders: Counts the distinct "order_id" values to obtain the total number of orders made.
5.Average Pizzas Per Order: Divides the sum of "quantity" by the count of distinct "order_id" values to calculate the average number of pizzas per order.

👉 Daily Trend of Total Orders: Groups the data by the day of the week ("order_date") and counts the distinct "order_id" values for each day.
👉 Hourly Trend of Total Orders: Groups the data by the hour of the order time ("order_time") and counts the distinct "order_id" values for each hour.
👉 Percentage of Sales by Pizza Category: Calculates the total revenue and percentage of sales for each pizza category, based on the sum of "total_price" and the overall sum of "total_price" from the "pizza_sales" table.
👉 Percentage of Sales by Pizza Size: Calculates the total revenue and percentage of sales for each pizza size, based on the sum of "total_price" and the overall sum of "total_price" from the "pizza_sales" table.
👉 Total Pizzas Sold by Pizza Category: Groups the data by pizza category and calculates the sum of "quantity" for each category to determine the total quantity of pizzas sold.
👉 Top 5 Best Sellers: Groups the data by pizza name and calculates the sum of "quantity" for each pizza to identify the top 5 best-selling pizzas based on quantity sold.
👉 Top 5 Worst Sellers: Groups the data by pizza name and calculates the sum of "quantity" for each pizza to identify the top 5 worst-selling pizzas based on quantity sold.

After performing the SQL queries, an Excel workbook is generated, and pivot tables are created to facilitate chart creation. The project culminates in the development of an interactive dashboard that showcases the key performance indicators (KPIs) and presents insightful graphs, providing valuable visualizations and insights.

Final Dashboard
