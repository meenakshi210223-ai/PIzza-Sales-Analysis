# PIzza-Sales-Analysis

Pizza Sales Analysis Project 📌 Overview This project focuses on analyzing a pizza sales dataset using SQL and Excel to extract key business insights. The goal was to help improve sales strategy, inventory planning, and staffing decisions based on actual sales trends.

🛠️ Tools & Technologies MySQL – for querying and analyzing the dataset

Excel – for data summaries and basic visualization (pivot tables, charts)

📂 Dataset The dataset includes:

Pizza orders

Pizza types

Order dates & times

Quantity, price, and size of pizzas

🔍 Key Objectives Identify top 5 best-selling pizzas

Analyze hourly and daily sales trends

Find revenue by pizza category (e.g., Classic, Supreme, Veggie)

Determine busiest time slots for maximum sales

Use SQL GROUP BY, ORDER BY, RANK(), and DATE functions for insights

📊 Analysis Performed Total revenue and quantity sold per pizza

Hour-wise and day-wise order distribution

Ranked pizzas by sales using window functions

Created Excel charts to visualize peak sales hours and best-selling categories

🧠 Skills Demonstrated SQL querying & logic building

Data cleaning and transformation

Analytical thinking & business understanding

Excel-based data visualization

📎 Sample SQL Snippet sql Copy Edit SELECT pizza_name, SUM(quantity) AS total_sold FROM pizza_sales GROUP BY pizza_name ORDER BY total_sold DESC LIMIT 5; 📈 Key Takeaways Pepperoni Pizza was the highest-selling item

Peak sales occurred between 6 PM to 9 PM

Weekends saw the highest order volume

These insights can help in inventory management and staff scheduling

Basic: Retrieve the total number of orders placed. Calculate the total revenue generated from pizza sales. Identify the highest-priced pizza. Identify the most common pizza size ordered. List the top 5 most ordered pizza types along with their quantities.

Intermediate: Join the necessary tables to find the total quantity of each pizza category ordered. Determine the distribution of orders by hour of the day. Join relevant tables to find the category-wise distribution of pizzas. Group the orders by date and calculate the average number of pizzas ordered per day. Determine the top 3 most ordered pizza types based on revenue.

Advanced: Calculate the percentage contribution of each pizza type to total revenue. Analyze the cumulative revenue generated over time. Determine the top 3 most ordered pizza types based on revenue for each pizza category.

About
Pizza Sales Analysis

Resources
 Readme
 Activity
Stars
 0 stars
Watchers
 0 watching
Forks
 0 forks
Report repository
Releases
No releases published
Packages
No packages published
Footer
