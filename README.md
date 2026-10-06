# Restaurant-Order-Analysis
# Restaurant Order Analysis Using SQL

A MySQL project analyzing restaurant order and menu data to identify sales patterns, customer preferences and actionable business insights.

### Dataset & Schema

Database: `restaurant_db`

The dataset consists of two main tables:

- `order_details` — `order_details_id`, `order_id`, `order_date`, `order_time`, `item_id`
- `menu_items` — `menu_item_id`, `item_name`, `category`, `price`

The `item_id` in `order_details` is connected to `menu_item_id` in `menu_items`.

### Analysis Performed

- Total orders and items sold
- Most frequently ordered items
- Highest-revenue category
- Highest-value orders
- Busiest day and hour
- Top 5 highest-value orders
- Menu pricing and category analysis

### Business Insights & Decisions

- Popular items → Support inventory planning and reduce stock shortages.
- High-revenue categories → Guide menu optimization and promotional strategies.
- Peak hours → Help optimize staff allocation during busy periods.
- High-value orders → Provide opportunities for upselling and combo offers.
- Pricing and demand patterns → Support menu pricing and product decisions.

### Tools & SQL Concepts

MySQL | SQL | MySQL Workbench

Concepts used: JOINs, GROUP BY, aggregate functions, subqueries, CTEs, views and date/time functions.

### Conclusion

The analysis found that Italian cuisine was the most popular category and generated the highest revenue. It also highlighted the most frequently ordered items, highest-value orders and peak ordering periods, providing insights that can support decisions around menu planning, inventory, staffing and promotional strategies.
