Credit Card Transaction Power BI Dashboard


This repository contains a Power BI dashboard that visualizes insights from credit card transaction data. 
The project demonstrates end-to-end data handling from raw CSV files to PostgreSQL integration and dynamic reporting using Power BI.


========== Tech Stack ==========

Power BI Desktop: Dashboard creation & visualization
PostgreSQL: Relational database to store processed CSV data
CSV: Source data format


========== Project Overview ==========

The objective was to build an interactive dashboard to analyze customer transactions, revenue, interest, and behavioral patterns across various demographics and card types. 
The dashboard helps identify profitable customer segments, transaction patterns, and delinquency trends.


========== Data Pipeline ==========

Data Source: Credit card transaction data in CSV format.
Database Layer: CSV data imported into a PostgreSQL database.
ETL Process: Light cleaning and transformation in SQL.
Power BI Integration: PostgreSQL connected to Power BI for real-time visual updates.

========== Dashboard Highlights ==========

Customer Transaction Report:

Revenue by Expense Type: Top categories include Bills, Entertainment, Fuel, and Grocery.

Demographics Breakdown:
Age group 40-50 and 50-60 dominate revenue.

*Highest contribution by Graduate and Businessman segments.
*Highest revenues from Blue cardholders.
*Geography: Top states include TX, NY, and CA.

Card Transaction Report:

*Total Revenue: $55.3M
*Total Interest Earned: $7.8M
*Transactions Count: 655.7K

Card Usage Type:
Most common: Swipe (35M revenue)
Others: Chip and Online
