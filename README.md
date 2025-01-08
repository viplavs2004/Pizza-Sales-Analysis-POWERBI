# Pizza Sales Revenue Analysis - Power BI

## Project Overview

This project is a comprehensive analysis of pizza sales data for Plato's Pizza, a Greek-inspired pizza place in New Jersey. The goal is to help the restaurant optimize its operations by analyzing transactional data and identifying key trends, insights, and opportunities for improvement. 

The analysis includes multiple aspects such as sales revenue trends, peak sales periods, best and worst-selling pizzas, average order values, and seating utilization.

### Key Questions Addressed:
1. What days and times are we busiest?
2. How many pizzas are we making during peak periods?
3. What are the best and worst-selling pizzas?
4. What's the average order value?
5. How well are we utilizing our seating capacity (15 tables and 60 seats)?

## Data Source

The dataset used in this analysis contains 12 key features related to pizza orders:
- `order_id`: Unique identifier for each order placed.
- `order_details_id`: Unique identifier for each pizza placed within an order.
- `pizza_id`: Unique identifier for each pizza type and its details.
- `quantity`: Quantity of each pizza ordered.
- `order_date`: Date the order was placed.
- `order_time`: Time the order was placed.
- `unit_price`: Price of a single pizza.
- `total_price`: Total price of the pizza order (`unit_price * quantity`).
- `pizza_size`: Size of the pizza (Small, Medium, Large, etc.).
- `pizza_type`: Type of pizza ordered.
- `pizza_ingredients`: Ingredients used in the pizza.
- `pizza_name`: Name of the pizza as shown on the menu.

The data was collected over the course of a year, providing a comprehensive view of pizza sales for Plato's Pizza.

## Objective

The primary objectives of this project are to:
1. **Identify trends**: Analyze pizza sales to understand busy times and days, the most popular pizza types, and peak sales periods.
2. **Optimize operations**: Provide actionable insights to help improve revenue and efficiency.
3. **Visualize Key Metrics**: Use Power BI to create engaging and informative visualizations to assist Plato's Pizza in decision-making.

## Tools Used
- **Power BI**: For creating interactive visualizations and reports.
- **Pandas**: (If preprocessing in Python is part of the workflow before loading into Power BI).
- **Data Visualization**: Various chart types like bar charts, line charts, pie charts, and scatter plots to visualize trends.

## Analysis and Insights

- **Busiest Days & Times**: Using sales data and timestamps, the analysis identifies peak hours and days.
- **Pizza Popularity**: Analyzes which pizza types are selling the most and which are underperforming.
- **Order Value Trends**: The average order value is calculated to assess overall customer spending patterns.
- **Seating Utilization**: Insights into seating capacity utilization to optimize table management.

## How to Use the Dashboard

1. **Clone this repository** to your local machine.
2. **Open the Power BI report** in Power BI Desktop or publish it to Power BI Service.
3. Explore the **interactive dashboards** to analyze sales trends, peak times, and pizza performance.
4. Use the insights to optimize menu offerings, pricing strategies, and operational efficiency.

## Key Features

- **Sales Revenue Over Time**: Visualizes total revenue by day, week, or month.
- **Pizza Type Performance**: Breakdown of pizza sales by type and size.
- **Order Value Distribution**: Shows the average and distribution of order values.
- **Peak Sales Periods**: Identifies busy times and days with the highest volume of orders.
- **Seating Utilization**: Analyzes table and seat occupancy rates.

## Installation

To use the Power BI file:
1. Clone this repository or download the `.pbix` Power BI file.
2. Open Power BI Desktop.
3. In Power BI Desktop, go to **File > Open** and select the `.pbix` file from the downloaded repository.

If you're interested in replicating the analysis or want to use your own dataset, make sure your dataset follows the same structure as the sample data provided.

## Contributing

Feel free to fork this repository and make contributions. If you find ways to improve the analysis or have new ideas for visualizations, please submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to [Maven Analytics](https://www.mavenanalytics.io/blog/maven-pizza-challenge) for providing the dataset.
- Special thanks to Plato's Pizza for allowing the use of their transactional data for analysis.

---

Enjoy exploring the Pizza Sales Revenue Dashboard, and I hope it helps Plato's Pizza optimize their operations and boost sales!

