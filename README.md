# Plato-s-Pizzas

## Introduction
Things are going OK here at Plato’s, but there’s room for improvement. They’ve been collecting transactional data for the past year, but really haven’t been able to put it to good use. Hoping we can analyze the data and put together a report to help us find opportunities to drive more sales and work more efficiently.

## Dataset Dictionary
- order_id: Unique identifier for each order placed by a table
- order_details_id: Unique identifier for each pizza placed within each order (pizzas of the same type and size are kept in the same row, and the quantity increases)
- pizza_id: Unique key identifier that ties the pizza ordered to its details, like size and price quantity: Quantity ordered for each pizza of the same type and size
- order_date: Date the order was placed (entered into the system prior to cooking & serving)
- order_time: Time the order was placed (entered into the system prior to cooking & serving)
- unit_price: Price of the pizza in USD
- total_price: unit_price * quantity
- pizza_size: Size of the pizza (Small, Medium, Large, X Large, or XX Large)
- pizza_type: Unique key identifier that ties the pizza ordered to its details, like size and price
- pizza_ingredients: ingredients used in the pizza as shown in the menu (they all include Mozzarella Cheese, even if not specified; and they all include Tomato Sauce, unless another sauce is specified)
- pizza_name: Name of the pizza as shown in the menu

To carry out this analysis, the following tools were employed: Power Query, Excel and Power BI

# Below is the outline of this analysis process
- Findings
- Answer Business Questions and Perform Exploratory Data Analysis
- DASHBOARD PRESENTATION
- Insights and recommendation

# FINDING
- Year considered — 2015
- Revenue — $817.86k
- Total_Orders — 21,350
- Number_of_pizza_types — 32
- Average order value — $38.31

# BUSINESS QUESTION
1. What days and times do we tend to be busiest?
2. What are our best and worst-selling pizzas?
3. What’s our average order value?
4. How much money did we make this year? Can we identify any seasonality in the sales?

Full documentation of this project is on my [medium](https://medium.com/@mb_awak/platos-pizza-sales-analysis-599f40f7ffaf).
## INSIGHTS AND RECOMMENDATION

# INSIGHTS
- A total of $8 was generated as revenue in 2015.
- The busiest time of the day is between 12pm and 1pm which is Lunch break and again at 5pm — 7pm. On weekends, the highest sales were recorded between 5pm — 7pm
- The busiest days are Thursday and Friday having a total of 6,777 orders
- The best selling Pizza is the Thai Chicken Pizza (large size) recording $43K in sales.
- Difference in sales contribution by pizza category was not too wide, top category — Classic Deluxe pizza generated $220k revenue while the least categories — Veggie generated $194 revenue.
- The months of March, May, July and November proved to be the best months in the year. The month of July garnered the highest revenue with 72.6 million dollars
- The highest sold pizza size is the Large size with a total of 18,526 orders placed for it, the least sold pizza size is the XXLarge with just 28 orders.

# RECOMMENDATION
- Save over $7,000 in operations costs by changing hours of operation to 12pm, 1pm, 5pm — 7pm daily.
- Since more orders are received on Fridays, a discount policy can be introduced every last Friday of the month where a customer gets 1 extra pizza when they buy 3 and above, this policy will encourage them to buy more.
- December has the lowest sales, hence promo and discount should be done during this period to increase sales.
- The ingredients for Pepperoni pizza should be made readily available and in large quantities to avoid shortage of ingredients.
- Remove Brie Carre from menu and replace with XL option for Barbecue chicken, Thai chicken or Cali chicken decreasing ingredient costs and increasing profit margin.
