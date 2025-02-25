# Data-Mart-Analysis-Project
The Data Mart Analysis Project utilized SQL to effectively process, clean, and analyze sales data, transforming raw information into actionable insights. This project began with the establishment of a database and table designed to store weekly sales data, encompassing attributes such as region, platform, customer type, and sales figures. The initial phase focused on data setup and cleansing, where SQL transformations were applied to enhance data quality. This included replacing null segments with "Unknown," categorizing customers into age bands (e.g., "Young Adults," "Retirees"), defining demographics as "Couples" or "Families," and calculating the average transaction value for each record.

Exploratory Data Analysis:
Following the data cleansing, the project progressed to exploratory data analysis (EDA), where SQL queries were employed to uncover trends and patterns within the dataset. Key insights included identifying missing week numbers by comparing available weeks against a pre-generated sequence. The analysis also calculated total transactions per year, providing a comprehensive overview of sales activity over time. Regional sales trends were examined by analyzing monthly sales across different regions, highlighting performance variations by location. Additionally, platform performance was assessed by determining the total transactions by platform, which helped gauge the popularity of each sales channel.

Advanced Insights:
The project further delved into advanced insights by comparing sales percentages between Retail and Shopify platforms on a monthly basis, revealing which platform was dominant during specific periods. An analysis of demographic contributions provided a deeper understanding of how different customer segments impacted yearly sales. Furthermore, the project identified which age bands and demographics contributed most significantly to Retail sales, offering valuable information for refining marketing strategies.

This project involves creating a data mart to analyze and explore weekly sales data across multiple years. The goal is to transform raw sales data into actionable insights by applying data cleansing and transformation techniques.

Key Features:

Data Cleansing: The project starts by cleaning the raw sales data. This includes adding week numbers, month numbers, and calendar years to each week's data. It also involves mapping segment values to age bands and demographics, handling null values, and calculating average transaction values.

Data Transformation: The cleaned data is then transformed into a structured format suitable for analysis. This includes creating new columns for age bands and demographics based on existing segment data.

Data Exploration: The transformed data is used to explore various aspects of sales trends. This includes identifying missing week numbers, calculating total transactions by year, analyzing sales by region and month, and determining transaction counts by platform.

Sales Analysis: The project provides insights into sales percentages by platform (Retail vs Shopify) for each month and by demographic for each year. It also identifies which age bands and demographics contribute most to Retail sales.

Tools and Technologies:

SQL: Used for data cleansing, transformation, and exploration.

Data Mart: The final structured dataset is stored in a data mart for easy querying and analysis.

Outputs:

Cleaned and Transformed Data: A new table named clean_weekly_sales containing the transformed data.

Insights and Trends: Various SQL queries provide insights into sales trends, customer demographics, and platform performance.
