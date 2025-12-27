# Monday Coffee Expansion SQL Project ☕

## Objective
The goal of this project is to analyze the sales data of Monday Coffee, a company that has been selling its products online since January 2023, and recommend the top three major cities in India for opening new coffee shop locations based on consumer demand and sales performance.

---

## Key Business Questions

1. **Coffee Consumers Count**  
   How many people in each city are estimated to consume coffee, assuming 25% of the population consumes coffee?

2. **Total Revenue from Coffee Sales**  
   What is the total revenue generated from coffee sales across all cities in the last quarter of 2023?

3. **Sales Count for Each Product**  
   How many units of each coffee product have been sold?

4. **Average Sales Amount per City**  
   What is the average sales amount per customer in each city?

5. **City Population and Coffee Consumers**  
   List cities along with their population and estimated coffee consumers.

6. **Top Selling Products by City**  
   What are the top 3 selling products in each city based on sales volume?

7. **Customer Segmentation by City**  
   How many unique customers are there in each city who have purchased coffee products?

8. **Average Sale vs Rent**  
   Find each city’s average sale per customer and average rent per customer.

9. **Monthly Sales Growth**  
   Calculate the percentage growth or decline in sales on a monthly basis.

10. **Market Potential Analysis**  
    Identify the top 3 cities based on highest sales, returning:
    - City name  
    - Total sales  
    - Total rent  
    - Total customers  
    - Estimated coffee consumers  

---

## Final Recommendations

Based on the analysis, the top three cities for new coffee shop expansion are:

### ☕ Pune
- Average rent per customer is very low  
- Highest total revenue  
- High average sales per customer  

### ☕ Delhi
- Highest estimated coffee consumers (~7.7 million)  
- High total number of customers (68)  
- Average rent per customer is reasonable (under 500)  

### ☕ Jaipur
- Highest number of customers (69)  
- Very low average rent per customer (156)  
- Strong average sales per customer (~11.6k)  

---

## Tools Used
- PostgreSQL  
- pgAdmin 4  
- SQL (Joins, Aggregations, CTEs, Window Functions)
