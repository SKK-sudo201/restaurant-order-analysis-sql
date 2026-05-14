# restaurant-order-analysis-sql
Restaurant Order Analysis Using SQL

## Project Overview
This project analyzes restaurant order data using SQL to understand menu performance, order trends, and customer purchasing behavior. The goal was to identify which menu items are performing well, which items are less popular, and what high-value customers tend to order.

## Tools Used
- MySQL
- MySQL Workbench
- SQL
- GitHub

## Dataset
The project uses two tables:

### menu_items
Contains menu item details such as item name, category, and price.

### order_details
Contains customer order details such as order ID, order date, order time, and item ID.

## Objectives

### 1. Explore Menu Items
- Counted total menu items
- Identified the least and most expensive items
- Analyzed Italian dishes
- Calculated item count and average price by category

### 2. Explore Orders
- Reviewed order date range
- Counted total orders and total items ordered
- Identified orders with the highest number of items
- Counted orders with more than 12 items

### 3. Analyze Customer Behavior
- Joined menu and order tables
- Identified the most and least ordered items
- Found the top 5 highest-spending orders
- Analyzed customer preferences in high-value orders

## Key SQL Skills Demonstrated
- SELECT statements
- WHERE filtering
- ORDER BY
- GROUP BY
- Aggregate functions
- JOINS
- Subqueries
- Business analysis using SQL

## Key Insights
- Certain menu categories generated higher order volume.
- High-value orders often included multiple items across different categories.
- Price and popularity did not always align, showing the importance of analyzing both sales volume and revenue.
- SQL joins helped connect customer orders with menu item details for deeper analysis.

## Business Recommendations
- Promote high-performing menu items through combo offers.
- Review low-performing items for pricing, placement, or possible removal.
- Use high-spend order patterns to design meal bundles.
- Track category-level performance regularly to support menu planning.

## Project Files
- dataset/ contains raw data files.
- sql/ contains SQL queries for each objective.
- screenshots/ contains query result screenshots.
- insights/ contains written business insights.
