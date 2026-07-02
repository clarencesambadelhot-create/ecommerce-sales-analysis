E-Commerce Sales Analysis (Python) - Smartphone and gadget company

An end-to-end data analysis project utilizing Pandas, Matplotlib, and Seaborn to solve real-world business challenges for an electronics retailer.

Business Objectives
The goal of this project was to analyze over 116,000 sales records to answer 4 strategic questions:
1. Identify the best month of the year in terms of revenue.
2. Determine which city registered the maximum number of orders.
3. Establish the ideal hours to display digital advertisements.
4. Pinpoint the top-selling product by volume.

Tech Stack & Key Methods
Language: Python
Libraries: Pandas, NumPy, Matplotlib, Seaborn, Glob
Data Cleaning: Handling missing values (`NaN`), scrubbing duplicated header rows, and converting data types (strings to numeric and datetime format).
Feature Engineering: Text-parsing extraction (isolating cities from raw addresses) and time-series extraction (isolating hours and months).

Key Business Insights
* **Peak Revenue:** December emerged as the highest revenue month with total sales exceeding **$4.61M** (driven heavily by holiday shopping).
* **Top Market:** **San Francisco** was the leading city with **50,239 items sold**.
* **Ad Optimization:** Order distribution peaks sharply at **11:00 AM** and **7:00 PM**. The business recommendation is to schedule promotional campaigns 30–60 minutes prior to these windows.
* **Core Product:** **AAA Batteries (4-pack)** was the most sold product with **31,017 units sold**.
