
# ☕ Monday Coffee Expansion SQL Project



---

## 📌 Objective

The goal of this project is to analyze the sales data of **Monday Coffee**, a company that has been selling its products online since January 2023.

Using SQL, this analysis identifies customer demand, sales performance, and city-level trends to **recommend the top three major cities in India** for opening new physical coffee shop locations.

---

## 🗂️ Dataset & Tools

- **Database:** PostgreSQL  
- **Tools Used:** pgAdmin, SQL  
- **Tables Used:**
  - `city`
  - `customers`
  - `products`
  - `sales`

---

## ❓ Key Business Questions

1. **Coffee Consumers Count**  
   How many people in each city are estimated to consume coffee, assuming 25% of the population drinks coffee?

2. **Total Revenue from Coffee Sales**  
   What is the total revenue generated from coffee sales across all cities in the last quarter of 2023?

3. **Sales Count for Each Product**  
   How many units of each coffee product have been sold?

4. **Average Sales Amount per City**  
   What is the average sales amount per customer in each city?

5. **City Population and Coffee Consumers**  
   Provide a list of cities along with their populations and estimated coffee consumers.

6. **Top Selling Products by City**  
   What are the top 3 selling products in each city based on sales volume?

7. **Customer Segmentation by City**  
   How many unique customers in each city have purchased coffee products?

8. **Average Sale vs Rent**  
   Find each city’s average sale per customer and average rent per customer.

9. **Monthly Sales Growth**  
   Calculate the percentage growth or decline in sales on a monthly basis.

10. **Market Potential Analysis**  
    Identify the top 3 cities based on highest sales and return:
    - City name  
    - Total sales  
    - Total rent  
    - Total customers  
    - Estimated coffee consumers  

---

## 📊 Recommendations

Based on the data analysis, the following cities are recommended for new coffee shop openings:

### ☕ Pune
- Lowest average rent per customer  
- Highest total revenue  
- Strong average sales per customer  

### ☕ Delhi
- Highest estimated coffee consumers (~7.7 million)  
- Large customer base (68 customers)  
- Average rent per customer (~330), still affordable  

### ☕ Jaipur
- Highest number of customers (69)  
- Very low average rent per customer (~156)  
- Healthy average sales per customer (~11.6k)  

---

## ✅ Conclusion

This SQL-based analysis highlights cities with strong demand, high revenue potential, and manageable operational costs.  
The findings support **data-driven expansion decisions** for Monday Coffee’s physical store locations.
