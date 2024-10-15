# DATACO-Supply-Chain-Analysis
  Project Brief: Analysis of DataCo Supply Chain Dataset
Overview: DataCo is a global e-commerce company that operates an online merchandise store, shipping products to customers worldwide from a central hub located in Asia. The dataset provided contains comprehensive information related to various aspects of the business, including customer details, order transactions, shipping logistics, product information, and more.
Objective: The primary goal of this project is to analyze the provided dataset to generate meaningful insights that can help enhance the business operations of DataCo. By interpreting key trends, patterns, and performance metrics, the analysis will aim to offer actionable recommendations for optimizing efficiency and decision-making across the supply chain.
Resources: The dataset is accompanied by a detailed data dictionary that defines each column and its purpose. This resource will serve as a guide to ensure accurate interpretation of the dataset variables.
Deliverables:
•	In-depth analysis of the dataset
•	Insights and recommendations to support DataCo’s operational and strategic goals
•	Data visualizations to effectively communicate findings

DASHBOARD BUILDING/DATA ANALYSIS OVERVIEW
Given the volume of the dataset, the analysis will be divided into the following key segments, with each segment represented on a separate page within the dashboard. The segments and their focus areas are as follows:
1.	Geographical Analysis:
	Focus: Analyze business performance across different regions.
	Metrics: Sales distribution by country, revenue by region, customer base per region, shipping locations, and regional performance comparisons.
	Visualizations:  geographical maps.
2.	Product Analysis:
	Focus: Evaluate product performance, customer preferences, and sales trends.
	Metrics: Best-selling products, product categories performance, product profitability, order quantity per product, and product return rates.
	Visualizations: Bar charts, pie charts, product performance KPIs, category comparison visuals.
3.	Shipping and Delivery Analysis:
	Focus: Assess shipping efficiency and delivery performance.
	Metrics: On-time deliveries, late deliveries, days for shipping (actual vs. scheduled), shipping cost analysis, and delivery risk metrics.
	Visualizations: Line graphs, scatter plots for delivery times, shipping performance KPIs, and comparative visuals for scheduled vs. actual shipping days.
4.	Trend Analysis:
	Focus: Examine business trends over time, including sales, profits, customer growth, and seasonal fluctuations.
	Metrics: Monthly/quarterly sales trends, order growth, seasonal sales performance, and profit margin trends over time.
	Visualizations: Time series line charts, trend indicators, monthly/quarterly comparison visuals.
Each segment will be featured on a dedicated dashboard page, ensuring clarity and ease of navigation for comprehensive data analysis. This approach will allow for focused insights and a structured understanding of different areas of DataCo's operations.
Geographical Analysis:
a.	Dashboard Page Design:
o	At the top of the page, display cards showing the following key metrics: DONE
	Customer Population
	Total Sales Recorded
	Total Profit Generated
	Total Quantity Ordered
b.	Create New Column for Total Profit:
o	Use the following DAX Query to create a new column named TotalProfit: DONE   
TotalProfit = [Profit Per Order] * [Quantity Ordered]
o	This will calculate the total profit based on the quantity of products ordered.
c.	Country-Based Visualizations:
o	Display a map to show the Quantity Ordered in each Order Country. Done
d.	Country-Level Profit:
o	Display Profit Sold in Each Country using a bar chart for easy comparison. Done
e.	Customer Population by Country:
o	Visualize the Customer Population in Each Order Country using a bar chart or  map. Done  
f.	Filter by Region:
o	Add a filter for Order Region to the page, allowing users to slice the data by region.

Shipping and Delivery Analysis:
a.	Dashboard Page Design:
o	Display the Number of Orders per Delivery Status using a bar chart or pie chart. Done
b.	Shipping Mode Distribution:
o	Show the Distribution Across Different Shipping Modes using a pie chart or bar chart. Highlight which shipping mode is the most utilized. Done
c.	Payment Option Distribution:
o	Display the Distribution Across Different Payment Options using a pie chart to show how customers are paying. Done
d.	Order Status Analysis:
o	Show the Number of Orders in Each Order Status and highlight the leading status in DataCo's customer orders using a bar chart. Done
e.	Late Delivery Risk Update:
	Replace Values in Power Query: In Power Query Editor, follow these steps to update the values in the Late Delivery Risk column:
	Select the Late Delivery Risk column.
	Use the Replace Values function to:
	Replace 1 with "Late".
	Replace 2 with "Not Late".
	Apply and close the query. Done
	Create a Pie Chart for Delivery Risk:
o	After the transformation is applied, use a pie chart to visualize the distribution of deliveries that are late versus those that are on time.
o	The chart will display the proportion of "Late" and "Not Late" deliveries to show the probability of a delivery being late.

Product Analysis:
a.	Dashboard Page Design:
o	Best-Selling Department (by sales): Display a bar chart showing the department with the highest total sales.
o	Fastest-Selling Department (by quantity ordered): Use a bar chart to show which department has the highest quantity ordered. Done
b.	Top 20 Categories (by sales): Display the Top 20 Category Names by Sales in a bar chart. 
c.	Bottom 20 Categories (by quantity ordered): Show the Bottom 20 Categories by Quantity Ordered using a bar chart. Done
d.	Add a Market Filter: Include a Market Filter on the product analysis page for market segmentation. Done

Trend Analysis:
a.	Dashboard Page Design:
o	Graph 1: Display a line graph showing the Quantity Ordered on a Monthly Basis. Use the order date to group by months.
o	Graph 2: Display another line graph showing Total Profit on a Monthly Basis. Done
b.	Filters:
o	Add a Date (Year) Filter to the page using the order date column, allowing users to filter by specific years.
o	Also, add an Order Region Filter to the page for regional trend analysis.


Report Writing
Give a detailed report summarizing your analysis of DataCo Supply Chain Store. What are the major challenges the business is facing and how can it be tackled.
Give wholistic recommendations to the management team.


https://app.powerbi.com/links/ASCKZ7UTsp?ctid=cc5894f0-eaa8-4da0-ab90-fd7a73e8a8f3&pbi_source=linkShare&bookmarkGuid=4bb6dd83-d08f-4f64-a960-eeb18cb6deb2
