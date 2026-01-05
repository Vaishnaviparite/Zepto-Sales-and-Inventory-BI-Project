## Project Overview 
This project uses a Zepto sales and inventory dataset to analyze product performance, pricing behavior, and stock availability patterns. Using Microsoft Power BI, the goal is to evaluate category‑wise sales, discount trends, product demand, and out‑of‑stock frequency to improve business planning and decision‑making in retail operations.

## <img width="980" height="759" alt="Screenshot 2025-11-10 005919" src="https://github.com/user-attachments/assets/40192c24-ace2-42a5-9f16-5e6cefa13b69" />

## Dataset Description
The dataset contains detailed information about products, sales, pricing, and availability, including:

•	Product Details: Category, Product Name, Weight  

•	Sales Metrics: Quantity Sold, Total Revenue, MRP, Selling Price  

•	Discount Metrics: Discount Percent, Discount Price Difference, Total Discount Amount 

This data supports analysis of sales behavior, pricing strategy effectiveness, and inventory efficiency across multiple product segments.

## Business Objectives
The primary objectives of this BI analysis are:

•	Identify high‑performing product categories  
•	Compare discount percentage vs selling price behavior  
•	Analyze out‑of‑stock frequency and availability trends  
•	Study most best-selling products and their revenue contribution  
•	Develop interactive dashboards to explore product metrics with filters

## Tools & Techniques
Microsoft Power BI

•	Data Cleaning & Transformation:

o	Used Power Query to remove blanks, fix inconsistent labels, and convert data types.
o	Corrected category formatting & numerical fields
o	Calculated additional fields to derive revenue & discount metrics
•	DAX Measures Created:
o	Total Revenue = SUM('Zepto'[Total Revenue])
o	Total Product Sold = SUM('Zepto'[quantity])
o	Avg Discount % = AVERAGE('Zepto'[discountPercent])
o	Avg Selling Price = AVERAGE('Zepto'[discount Selling Price])
o	Out‑Of‑Stock Count = SUM('Zepto'[outOfStock])

•	Visuals Used:

o	 Card Visuals: Total revenue, products sold, discount %, avg selling price, stock‑outs  
o	 Clustered Column Chart: Category quantity comparison  
o	 Donut Chart: Out Of Stock Distribution  
o	 Line Chart: Discount vs selling price trend  
o	 Bar Chart: Top 10 products by quantity  
o	 Area Chart: Category‑wise revenue comparison  
o	 Scatter Chart: Selling price vs discount percentage  
o	 Table: High‑discount products with values  
o	 Filters/Slicers: Category, Product name

## Deliverables

•	Cleaned Power BI dataset with transformed fields.
•	Interactive dashboard summarizing product and inventory insights  
•	KPI metrics for sales, pricing, and stock health  
•	Word-based summary report (this document).

## Key Insights

•	Chocolates & Candies, Dairy, Cooking Essentials and Beverages categories generate significant sales volume .
•	Certain products showed high discount dependency for demand generation .
•	Multiple highly‑sold products showed out‑of‑stock behavior, indicating strong demand. 
•	Category comparison chart shows distinct performance variation across product groups.
•	Scatter graph shows limited correlation between selling price and discount percentage for certain categories

## Future Enhancements

•	Add time‑based trend analysis for week/month sales  
•	Include customer segmentation and retention patterns  
•	Build ML model for demand forecasting  
•	Integrate automated inventory alerting for critical stock levels
