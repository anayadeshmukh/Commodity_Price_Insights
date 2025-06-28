# Commodity_Price_Insights
SQL Project

# PricePulse: A Data-Driven Analysis of Commodity Price Trends Across Regions (2019–2020)

## Database: `commodity_db`

This project aims to analyze key aspects of a commodity price database by focusing on **price variations**, **regional disparities**, **variety distribution**, and **state-wise availability patterns**.

---

## Business Objective

The goal of this project is to uncover patterns and disparities in commodity pricing across different regions of India from **January 2019 to December 2020**, using structured SQL queries and analysis. This study provides critical insights into:

* **Market volatility** is identified by identifying commodities with the highest price variation.
* **Regional pricing gaps** can signal inefficiencies in distribution or differences in demand.
* **Commodity diversity**, analyzing the number of varieties for each commodity.
* **State-wise insights**, especially focusing on under-represented regions with fewer data points.

These insights can assist in policy-making, logistics optimization, and price monitoring for businesses, governments, and consumers.

---

## Queries

### Business Problem 1: Common commodities in the Top 10 costliest (Avg price) in 2019 & 2020?
![image](https://github.com/user-attachments/assets/3ce1f697-a011-4244-a91f-27f08cc4d852)

### Output
commodity     | 
--------------|-----
Shoes-Gents   |
Coffee        |
Black Pepper  |
Soft Cake     |
Meat          |
Saree         |
Ghee          |

---

### Business Problem 2: Max price difference for any commodity in June 2020 (which commodity)?
![image](https://github.com/user-attachments/assets/b530f1e8-8407-4c96-a547-a1bb004f3660)

### Output
commodity  | max_diff   
-----------|--------------
Coffee	   | 2435.00

---

### Business Problem 3: Commodities by number of varieties → Get the 3rd highest?
![image](https://github.com/user-attachments/assets/33341c68-93e1-4a8d-a734-7d19f6f80a5f)

### Output
commodity  | variety_count   
-----------|-----------------
Coffee	   | 2

---

### Business Problem 4: In the state with the fewest data points → which commodity has the most entries?
![image](https://github.com/user-attachments/assets/6045951b-6cdd-4999-9e52-bfd7b00dfc13)

### Output
state              | commodity | data_count        
-------------------|-----------|---------------
Arunachal Pradesh  | Rice	     | 9   

---

### Business Problem 5: Which commodity & city had the highest price variation (Jan 2019 vs Dec 2020)?
![image](https://github.com/user-attachments/assets/4b010e4d-08f7-42b4-a1b4-c8e6f9f54aa6)

### Output
commodity | city    | jan_price | dec_price  | variation_abs | variation_pct      
----------|---------|-----------|------------|---------------|-----------------
Fish	    | Kurnool	| 50.000000	| 500.000000 | 450.000000	   | 900.00

---

## Tables Used

- `price_details` – id, region_id, commodity_id, date, retail_price
- `commodities_info` – id, commodity, variety 
- `region_info` – id, state, city 
 
---

## Tools & Skills

- SQL Joins (INNER JOIN, LEFT JOIN)
- Aggregations (MIN, MAX, COUNT, SUM)
- GROUP BY and ORDER BY operations
- Conditional filtering using WHERE and HAVING
- Date-based filtering and analysis

---

## Outcome

This project reveals actionable commodity market insights to:
* Detect price volatility across regions and periods
* Compare regional pricing differences for the same commodities
* Rank commodities based on variety availability
* Identify data gaps and commodity trends in under-represented states
* Highlight the most dynamic commodity-city pair for better market targeting

---
