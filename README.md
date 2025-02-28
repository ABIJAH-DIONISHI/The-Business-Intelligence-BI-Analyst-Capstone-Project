# The-Business-Intelligence-BI-Analyst-Capstone-Project
Business Scenario and Dataset Details
You have recently been appointed as a BI Analyst by a leading retail chain that operates globally, renowned for its diverse product offerings and commitment to customer satisfaction. In order to maintain its competitive edge and optimize business performance, the company is keen on leveraging data-driven insights to enhance sales strategies and operational efficiency.
As a BI Analyst, your primary responsibility is to conduct a comprehensive analysis of the sales performance of the retail chain across different regions and time periods. The objective is to identify key factors influencing sales, including store locations, product hierarchies, and promotional strategies. By delving into the sales data extracted from daily sales records, product hierarchy details, and store information, you will unravel valuable insights that inform strategic decision-making.
Your tasks will encompass the following:
•	Data Cleaning and Analysis:
Your initial task involves meticulously cleaning and analyzing the sales data using Excel. This includes conducting Sales Data Analysis, Sales by City Analysis, and Product Performance Analysis to gain a comprehensive understanding of sales trends and patterns.
•	Data Querying and Analysis:
Using PostgreSQL, you will create data cubes with ROLLUP, summarize data along hierarchies, and identify trends by combining time and geographical data. This will enable you to extract actionable insights to optimize sales strategies and stock management.
•	Chart Creation and Regression Analysis:
In this phase, you will focus on creating insightful charts using Excel and conducting regression analysis to uncover correlations between sales figures and dates. This analysis will provide valuable insights into sales trends and seasonal patterns, facilitating informed decision-making.
•	Data Visualization:
Harnessing the power of Tableau, you will create dynamic dashboards and visualizations to present key findings related to sales performance, regional sales analysis, product analysis, and store performance. Your visualization efforts will facilitate clear communication of insights and support strategic decision-making processes.
You will also develop a final project presentation in PowerPoint, where you will demonstrate your ability to derive actionable insights from data and communicate findings effectively to stakeholders.
Data Details
The data would normally come from the company’s own systems, but in this case we have taken the data from the Retail Sales Data data set at the Kaggle website.
Retail Sales Data
In the Kaggle data set, you will find the following three CSV files. - sales.csv - Daily sales data covering 2017-2019. - product_hierarchy.csv - Data containing the hierarchy and sizes of the products. - store_cities.csv - Data containing the store's city, type, and size information.
sales.csv - This csv file provides insights into product sales, revenue, stock levels, pricing, and promotional effectiveness across different stores and dates.
•	product_id - The unique identifier of a product (String)
•	store_id - The unique identifier of a store (String)
•	date - Sales date (YYYY-MM-DD)
•	sales - Sales quantity (Number)
•	revenue - Daily total sales revenue (Number)
•	stock - End of day stock quantity (Number)
•	price - Product sales price (Number)
•	promo_type_1 - Type of promotion applied on channel 1 (String)
•	promo_bin_1 - Binned promotion rate for applied promo_type_1 (String)
•	promo_type_2 - Type of promotion applied on channel 2 (String)
•	promo_bin_2 - Binned promotion rate for applied promo_type_2
•	promo_discount_2 - Discount rate for applied promo type 2
•	promo_discount_type_2 - Type of discount applied
product_hierarchy.csv - This csv file provides details about product dimensions such as length, depth, and width, along with cluster and hierarchy IDs.
•	product_id - The unique identifier of a product (String)
•	product_length - Length of product (Number)
•	product_depth - Depth of product (Number)
•	product_width - Width of the product (Number)
•	Cluster_id (String)
•	hierarchy1_id (String)
•	hierarchy2_id (String)
•	hierarchy3_id (String)
•	hierarchy4_id (String)
•	hierarchy5_id (String)
store_cities.csv - This csv file contains information about store identifiers, types, sizes, and the corresponding city identifiers.
•	store_id - The unique identifier of a store (String)
•	storetype_id (String)
•	store_size (Number)
•	city_id (String)
Modified Data
The dataset obtained from Kaggle contains 19.5 million entries, which far exceeds Excel's maximum row limit of around 1 million. If we were to use the entire dataset, cleaning and other operations would become prohibitively time-consuming, and Excel might eventually stop responding. For this reason, the sales.csv file has been truncated to approximately 600,000 rows of data for your use.
To enhance data understanding, readability, and analysis, we have included three additional CSV files and the existing three CSV files.
product_names.csv - This file links product identifiers with their corresponding names, providing a mapping for easier reference and analysis.
•	product_id (String)
•	product_name (String)
store_names.csv - This file associates store identifiers with their respective names, allowing for better identification and analysis of stores.
•	store_id (String)
•	store_name (String)
city_names.csv - This file maps city identifiers to their names, enabling geographical analysis and insights based on city-level data.
•	city_id (String)
•	city_names (String)

