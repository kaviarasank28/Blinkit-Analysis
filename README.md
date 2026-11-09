1•Project title

Blinkit Analysis"BUSINESS REQUIREMENT"To conduct a comprehensive analysis of Blinkit's sales performance, customer satisfaction, and inventory distribution to identify key insights and opportunities for optimization using various KPIs and visualizations in Power BI.

2•Short descripton
   
1.KPI’s Requirements;
   👉Total Sales: The overall revenue generated from all items sold.
   👉Average Sales: The average revenue per sale.
   👉Number of Items: The total count of different items sold.
   👉Average Rating: The average customer rating for items sold.
   
2.Granular Requirements;
  👉Total Sales by Fat Content:
	Objective: Analyze the impact of fat content on total sales.
	Additional KPI Metrics: Assess how other KPIs (Average Sales, Number of Items, Average Rating) vary with fat content.
  👉Total Sales by Item Type:
	Objective: Identify the performance of different item types in terms of total sales.
	Additional KPI Metrics: Assess how other KPIs (Average Sales, Number of Items, Average Rating) vary with fat content.
  👉Fat Content by Outlet for Total Sales:
	Objective: Compare total sales across different outlets segmented by fat content.
	Additional KPI Metrics: Assess how other KPIs (Average Sales, Number of Items, Average Rating) vary with fat content.
  👉Total Sales by Outlet Establishment:
	Objective: Evaluate how the age or type of outlet establishment influences total sales.

3.Chart’s Requirements;
  👉Percentage of Sales by Outlet Size:
	Objective: Analyze the correlation between outlet size and total sales.
  👉Sales by Outlet Location:
	Objective: Assess the geographic distribution of sales across different locations.
  👉All Metrics by Outlet Type:
	Objective: Provide a comprehensive view of all key metrics (Total Sales, Average Sales, Number of 	Items, Average Rating) broken down by different outlet         types.

3•Tech Stack;

List the key technologies used to build the dashboard.

Example:

The dashboard was built using the following tools and technologies:

📊Power BI Desktop - Main data visualization platform used for report creation.

📂Power Query - Data transformation and cleaning layer for reshaping and preparing the data.

🧠DAX (Data Analysis Expressions) - Used for calculated measures, dynamic visuals, and conditional logic.

📝Data Modeling - Relationships established among tables (resorts, snow, and data_dictionary) to enable cross-filtering and aggregation.

📁File Format .pbix for development and .png for dashboard previews.

4•DATA CLEANING:
Cleaning the Item_Fat_Content field ensures data consistency and accuracy in analysis. The presence of multiple variations of the same category (e.g., LF, low fat vs. Low Fat) can cause issues in reporting, aggregations, and filtering. By standardizing these values, we improve data quality, making it easier to generate insights and maintain uniformity in our datasets.
