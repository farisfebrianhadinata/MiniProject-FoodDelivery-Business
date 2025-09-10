# MiniProject-FoodDelivery-Business
**## Foodpanda Dataset Analysis ##**
**1. Project Goal**
This project aims to conduct an in-depth analysis of the Foodpanda dataset to gain valuable insights into customer behavior, order trends, and operational efficiency. The findings from this analysis can be used to optimize business strategies, improve customer satisfaction, and drive growth.

**2. Dataset Description**
This dataset contains Foodpanda transaction and customer data, including key information such as:
Customer Data: ID, gender, age, city, and sign-up date (customer_id, gender, age, city, signup_date).
Order Data: Order ID, date, restaurant, dish name, category, quantity, price, and payment method (order_id, order_date, restaurant_name, dish_name, category, quantity, price, payment_method).
Behavioral Data: Order frequency, loyalty points, churn status, rating, and delivery status (order_frequency, loyalty_points, churned, rating, delivery_status).

**3. Data Analysis Stages**
The analysis was conducted through several systematic stages to ensure data integrity and accuracy:

**Data Understanding:**
Examining the basic structure, dimensions, and data types of each column.
Analyzing initial descriptive statistics to understand data distribution.
Identifying missing values and duplicate data.

**Data Cleaning:**
Removing duplicate rows to ensure the data is unique.
Filling missing values in the rating column with the median value to maintain data integrity.

**Data Transformation:**
Converting date columns (signup_date, order_date, etc.) to datetime format.
Creating new features like order_month and price_per_item for more specific analysis.
Converting the churned column to a boolean type (True/False) for easier retention analysis.

**Exploratory Data Analysis (EDA):**
Performing simple aggregations to calculate the number of orders by city, gender, and payment method.
Identifying the most popular restaurants and dishes.

**4. Key Findings and Visualization Results**
From the data analysis and visualizations, several key insights were obtained:

Monthly Revenue Trends: A line graph shows the revenue trend over time, identifying sales peaks that likely occur during specific months, which could be an ideal time for promotional campaigns.
Restaurant Popularity: A bar chart shows that only a small number of restaurants account for the majority of orders. This highlights the key restaurant partners who are crucial to the business.
Impact of Service Quality: The analysis shows a direct link between delivery status and customer ratings. Orders that are delayed or canceled tend to receive significantly lower ratings, affirming the importance of logistics efficiency.
Loyalty Points: The distribution of loyalty points varies, allowing for effective customer segmentation. Customers with high loyalty points can be targeted for retention programs, while others can be targeted for acquisition.
Payment Preferences: A stacked bar chart shows that payment method preferences can vary between cities. This information is important for optimizing payment infrastructure and specific promotions in each location.

**5. Conclusion**
Overall, this project successfully provides a comprehensive overview of Foodpanda's business health. The data shows strong performance, but there is significant potential for improvement, especially in delivery efficiency and customer relationship management. By leveraging this data, the company can make more informed decisions to enhance customer satisfaction and drive sustainable growth.

**Contact**
For questions or collaboration, please feel free to reach out to me at [farisfebrianhadinata@gmail.com] or on LinkedIn [https://www.linkedin.com/in/faris-febrianhadinata].
