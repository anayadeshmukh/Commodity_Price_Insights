# Commodity_Price_Insights
SQL Project

## Commodity Price Intelligence: Analyzing Retail Price Volatility Across Regions (2019–2020) 

**Business Objective:**

The primary objective of this project is to analyze retail pricing trends and the availability of essential commodities across Indian regions for the years 2019 and 2020. This includes:

* Identifying the most expensive commodities over two years and analyzing overlaps.
* Measuring price disparities across regions to detect maximum regional price differences.
* Understanding commodity diversity by analyzing how many varieties each commodity has.
* Investigating regional data density to highlight underrepresented states and their key commodities.
* Measuring price variation trends across cities over time to identify highly volatile commodities.

These insights can help policymakers, supply chain analysts, and local businesses:

* Make data-driven decisions on subsidy targeting.
* Identify regions facing unequal access or inflated pricing.
* Optimize distribution strategies.
* Predict future price instability.

## Queries 
### Commodity DB
Business Problem 1: Common commodities in the Top 10 costliest (Avg price) in 2019 & 2020? 
![image](https://github.com/user-attachments/assets/7d952a62-9ea4-4549-975d-0db738608340)

Business Problem 2: Max price difference for any commodity in June 2020 (which commodity)?
![image](https://github.com/user-attachments/assets/992f4efe-b117-4075-b64f-622148264d39)

Business Problem 3: Commodities by number of varieties → Get the 3rd highest?
![image](https://github.com/user-attachments/assets/295b78cf-facf-49f0-a9e9-ccd70deae88a)

Business Problem 4: In the state with the fewest data points → which commodity has the most entries?
![image](https://github.com/user-attachments/assets/a24a1dcc-12dd-4585-b7e8-feb823fdb126)

Business Problem 5: Which commodity & city had the highest price variation (Jan 2019 vs Dec 2020)?
![image](https://github.com/user-attachments/assets/2ee6981f-2123-4417-b819-b92fd157c3c4)

### Supply Chain DB
Business Problem 1: Count of orders by type (exclude Sangli, Srinagar, and fraud)? 


Business Problem 2: Top 3 customers with max completed orders and total sales?


Business Problem 3: Order count by shipping mode & department (only if dept has ≥ 40 closed/completed orders)? 

Business Problem 4: Shipment Compliance: Which Shipping Mode Experiences the Most Delays?

Business Problem 5: State-wise cancellation percentage?

