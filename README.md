# E-CommerceDB
An interactive sales dashboard in Excel using historical e-commerce sales data, enabling stakeholders to gain insights into business performance by analyzing sales and profit trends across months, regions, and product categories.
Steps Taken:
1.	Data Understanding and Cleaning:
o	Reviewed all columns (Order ID, Order Date, Ship Mode, Product Category, Sales, Profit, etc.).
o	Checked for missing or incorrect data and corrected formatting (e.g., dates).

2.	Data Preparation:
o	Copied data from the raw dataset and used SUMIFS to create:
	Month-wise Sales & Profit.
	Region-wise Sales.

3.	Dashboard Elements Created:
o	Combo Box Control: Enabled user selection of a product category.
o	Column Charts:
	One showing month-wise trends (Sales and Profit).
	One showing region-wise performance.
o	Usage of Xlookup:
	Inserted columns (via Xlookup) to find total sales-profit according to month irrespective of product category.
	Similarly, for total sales of region irrespective of product category. 
o	Linked the combo box to dynamically update visuals based on selected category.
o	Applied filters and formatting for clean presentation.
________________________________________
Key Insights Derived:
•	Central Region consistently performed better in terms of sales volume.
•	Fashion category showed high sales as well as high profit margins.
•	Seasonal patterns are evident in some product categories.
