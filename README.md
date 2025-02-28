# The-Business-Intelligence-BI-Analyst-Capstone-Project
**Business Scenario and Dataset Details**
You have recently been appointed as a BI Analyst by a leading retail chain that operates globally, renowned for its diverse product offerings and commitment to customer satisfaction. In order to maintain its competitive edge and optimize business performance, the company is keen on leveraging data-driven insights to enhance sales strategies and operational efficiency.

As a BI Analyst, your primary responsibility is to conduct a comprehensive analysis of the sales performance of the retail chain across different regions and time periods. The objective is to identify key factors influencing sales, including store locations, product hierarchies, and promotional strategies. By delving into the sales data extracted from daily sales records, product hierarchy details, and store information, you will unravel valuable insights that inform strategic decision-making.

Your tasks will encompass the following:

**Data Cleaning and Analysis**

Your initial task involves meticulously cleaning and analyzing the sales data using Excel. This includes conducting Sales Data Analysis, Sales by City Analysis, and Product Performance Analysis to gain a comprehensive understanding of sales trends and patterns.

**Data Querying and Analysis**
Using PostgreSQL, you will create data cubes with ROLLUP, summarize data along hierarchies, and identify trends by combining time and geographical data. This will enable you to extract actionable insights to optimize sales strategies and stock management.

**Chart Creation and Regression Analysis**
In this phase, you will focus on creating insightful charts using Excel and conducting regression analysis to uncover correlations between sales figures and dates. This analysis will provide valuable insights into sales trends and seasonal patterns, facilitating informed decision-making.

**Data Visualization**
Harnessing the power of Tableau, you will create dynamic dashboards and visualizations to present key findings related to sales performance, regional sales analysis, product analysis, and store performance. Your visualization efforts will facilitate clear communication of insights and support strategic decision-making processes.

You will also develop a final project presentation in PowerPoint, where you will demonstrate your ability to derive actionable insights from data and communicate findings effectively to stakeholders.

Data Details
The data would normally come from the company’s own systems, but in this case we have taken the data from the Retail Sales Data data set at the Kaggle website.

**Retail Sales Data**
In the Kaggle data set, you will find the following three CSV files. - sales.csv - Daily sales data covering 2017-2019. - product_hierarchy.csv - Data containing the hierarchy and sizes of the products. - store_cities.csv - Data containing the store's city, type, and size information.

**_sales.csv_** - This csv file provides insights into product sales, revenue, stock levels, pricing, and promotional effectiveness across different stores and dates.

                       •	_product_id_ - The unique identifier of a product (String)
                       •	_store_id_ - The unique identifier of a store (String)
                       •	_date_ - Sales date (YYYY-MM-DD)
                       •	_sales_ - Sales quantity (Number)
                       •	_revenue_ - Daily total sales revenue (Number)
                       •	_stock_ - End of day stock quantity (Number)
                       •	_price_ - Product sales price (Number)
                       •	_promo_type_1_ - Type of promotion applied on channel 1 (String)
                       •	_promo_bin_1_ - Binned promotion rate for applied promo_type_1 (String)
                       •	_promo_type_2_ - Type of promotion applied on channel 2 (String)
                       •	_promo_bin_2_ - Binned promotion rate for applied promo_type_2
                       •	_promo_discount_2_ - Discount rate for applied promo type 2
                       •	_promo_discount_type_2_ - Type of discount applied
  
**product_hierarchy.csv** - This csv file provides details about product dimensions such as length, depth, and width, along with cluster and hierarchy IDs.

                      •	_product_id_ - The unique identifier of a product (String)
                      •	_product_length_ - Length of product (Number)
                      •	_product_depth_ - Depth of product (Number)
                      •	_product_width_ - Width of the product (Number)
                      •	_Cluster_id_ (String)
                      •	_hierarchy1_id_ (String)
                      •	_hierarchy2_id_ (String)
                      •	_hierarchy3_id_ (String)
                      •	_hierarchy4_id_ (String)
                      •	_hierarchy5_id_ (String)
  
store_cities.csv - This csv file contains information about store identifiers, types, sizes, and the corresponding city identifiers.

                     •	_store_id_ - The unique identifier of a store (String)
                     •	_storetype_id_ (String)
                     •	_store_size_ (Number)
                     •	_city_id_ (String)
  
**Modified Data**
The dataset obtained from Kaggle contains 19.5 million entries, which far exceeds Excel's maximum row limit of around 1 million. If we were to use the entire dataset, cleaning and other operations would become prohibitively time-consuming, and Excel might eventually stop responding. For this reason, the sales.csv file has been truncated to approximately 600,000 rows of data for your use.
To enhance data understanding, readability, and analysis, we have included three additional CSV files and the existing three CSV files.

**product_names.csv** - This file links product identifiers with their corresponding names, providing a mapping for easier reference and analysis.

                    •	_product_id_ (String)
                    •	_product_name_ (String)
  
**store_names.csv** - This file associates store identifiers with their respective names, allowing for better identification and analysis of stores.

                    •	_store_id_ (String)
                    •	_store_name_ (String)
  
**city_names.csv** - This file maps city identifiers to their names, enabling geographical analysis and insights based on city-level data.

                    •	_city_id_ (String)
                    •	_city_names_ (String)
  


