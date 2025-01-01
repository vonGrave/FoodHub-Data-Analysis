![foodhub](https://github.com/user-attachments/assets/bc175cda-4adf-46a6-bbfd-ab7dedefb0ab)


# FoodHub Order Analysis Project

## Project Overview
This project analyzes order data from FoodHub, a food delivery company, to understand customer behavior, delivery performance, and revenue patterns. The analysis provides insights into cuisine preferences, restaurant popularity, delivery timing, and customer satisfaction.

## Dataset Description
The dataset (foodhub_order.csv) contains information about food delivery orders with the following features:
- order_id: Unique identifier for each order
- customer_id: Unique identifier for each customer
- restaurant_name: Name of the restaurant
- cuisine_type: Type of cuisine (e.g., American, Japanese, Italian)
- cost_of_the_order: Cost of the order in dollars
- day_of_the_week: Weekday or Weekend
- rating: Customer rating (1-5, or "Not given")
- food_preparation_time: Time taken to prepare the food (in minutes)
- delivery_time: Time taken to deliver the order (in minutes)

## Key Findings
1. Cuisine Preferences
- American, Japanese, Italian, and Chinese cuisines account for ~80% of orders
- Shake Shack is the most frequently ordered from restaurant

2. Order Patterns
- Higher order volumes during weekends
- Faster delivery times during weekends (22 minutes vs 28 minutes on weekdays)

3. Delivery Performance
- 10.54% of orders take more than 60 minutes for total delivery
- Average delivery times are shorter on weekends

4. Customer Feedback
- Approximately 39% of orders lack customer ratings

## Revenue Analysis
Custom revenue calculation based on order cost:
- 25% revenue for orders > $20
- 15% revenue for orders > $5
- 0% revenue for orders ≤ $5
Total net revenue: $6,166.30

## Libraries Used
- numpy
- pandas
- matplotlib
- seaborn

## Business Recommendations
1. Focus partnerships on popular cuisine types (American, Japanese, Italian, Chinese)
2. Implement strategic promotions with high-performing restaurants
3. Optimize weekend operations with additional delivery capacity
4. Improve rating collection system to increase customer feedback
5. Implement delivery time optimization strategies to reduce delays

## Running the Analysis
1. Ensure all required libraries are installed
2. Place the foodhub_order.csv file in the working directory
3. Run the Jupyter notebook FoodHub_Data_Analysis.ipynb

## Future Work
- Detailed analysis of customer segmentation
- Predictive modeling for delivery times
- Geographic analysis of order patterns
- Customer retention analysis
