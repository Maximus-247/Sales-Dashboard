# Sales Performance Analysis for ABC Company
## Overview

The sales dashboard provides a comprehensive view of ABC Company's sales performance across multiple dimensions, including geography, salespersons, products, time periods, and customer preferences. The data used for this analysis was derived from different sources and techniques:
![image alt](https://github.com/Maximus-247/Sales-Dashboard/blob/main/GroupBY.png?raw=true)
![image alt](https://github.com/Maximus-247/Sales-Dashboard/blob/main/Having.png?raw=true)
![image alt](https://github.com/Maximus-247/Sales-Dashboard/blob/a5f61ea1417dc76f851b1ff95071250aa58c50e4/Join.png)
![image alt](https://github.com/Maximus-247/Sales-Dashboard/blob/67bbb5769755737c8e8db831729f4809041221be/DAX.png)
•	Sales data by weekday, geography, and product categories was extracted from an Oracle database using the GROUP BY function, summarizing total sales trends.

•	Filtered sales insights for specific conditions were obtained using the HAVING clause in SQL, allowing a deeper analysis of total sales by product, salespersons, and time period.

•	A detailed sales breakdown across multiple dimensions was achieved by joining multiple tables from the Oracle database, enabling cross-referencing of sales by region, category, and salesperson.

•	Advanced calculations for high and low sales performance were performed using DAX (Data Analysis Expressions) functions in Power BI, providing insights into trends over time and sales segmentation by region and product category.

•	Various visualization techniques such as bar charts, pie charts, treemaps, and line charts were utilized to present sales trends effectively.

These insights will help ABC Company optimize its sales strategy, improve resource allocation, and enhance decision-making processes.

# Problem Statement

ABC Company seeks to identify key factors influencing sales performance across different regions, weekdays, and product categories. While sales figures are available, the organization lacks actionable insights into which products perform best, the most profitable geographies, the effectiveness of sales representatives, and the impact of time trends on total sales. Understanding these metrics is crucial to refining marketing strategies, increasing revenue, and optimizing inventory management.

## Objectives
1.	Analyze Sales Trends Over Time – Determine the monthly and yearly variations in total sales.
  
2.	Evaluate Sales Performance by Geography – Identify the best and worst-performing regions.
  
3.	Assess Product Performance – Determine the most and least sold products.
   
4.	Measure Sales Representative Performance – Identify top-performing salespersons.
   
5.	Understand the Impact of Weekdays on Sales – Identify which days generate the highest revenue.
    
6.	Segment High and Low Sales Performance – Understand factors contributing to sales variations.
    
7.	Improve Sales Forecasting and Planning – Use insights from the dashboard to predict future sales patterns.

 ## Analysis of Results
1. Sales Performance by Weekday (Derived from Oracle using GROUP BY)
   
•	Sales fluctuate across the weekdays, with Weekday 2 showing the highest sales at 175K.

•	The least performing weekday is Weekday 3, generating 141K in total sales.

•	Possible reasons: Customer behavior trends—more purchases may occur on specific days due to promotions or work schedules.

•	Visualization Used: Bar chart displaying total sales by weekday.


3. Sales Performance by Month (Filtered using the HAVING Clause in Oracle)
   
•	The trend indicates a peak in January and December, with a significant decline from February to June.

•	Sales drop dramatically from February to May, suggesting seasonal variations or a lack of promotions.

•	Visualization Used: Line chart to track sales trends over months.


5. Geographic Sales Distribution (Summarized using GROUP BY in Oracle)
   
•	The highest sales figures are observed in New Zealand and the USA.

•	Regions like Canada and the UK report comparatively lower sales volumes.

•	Visualization Used: Geographical heat map.

7. Sales Performance by Product (Filtered using the HAVING Clause in Oracle)
   
•	50% Dark Bites is the highest-selling product.

•	Mint Chip Choco and Raspberry Choco follow closely, while Almond Choco has lower sales.

•	Visualization Used: Treemap and bar chart to show total sales by product.

9. Sales Performance by Salesperson (Filtered using the HAVING Clause in Oracle)
    
•	Dennison Crosswaite has the highest sales (328K), followed by Barr Faughny (305K).

•	Gunar Cockshoot records the lowest sales (140K).

•	Visualization Used: Horizontal bar chart ranking sales performance.


11. Regional Sales Performance (Derived from JOIN operations in Oracle)
    
•	The APAC region accounts for 57.2% of total sales, followed by the Americas at 29.35%.

•	Europe lags with only 13.45% of sales.

•	Visualization Used: Pie chart representing regional sales distribution.


13. High vs. Low Sales Categories (Derived from Power BI DAX functions)
    
•	The Milk Bars and Dark Bites categories dominate sales.

•	Some products, such as Eclairs and Almond Choco, are underperforming.

•	Visualization Used: Stacked bar chart for total sales by category and product.

________________________________________
## Conclusion:
The sales dashboard provides critical insights into ABC Company's sales trends, regional performance, product preferences, and salesperson contributions. The data shows seasonal trends, geographical disparities, and weekday variations, which can be leveraged for targeted business strategies. The integration of Oracle SQL (GROUP BY, HAVING, and JOIN operations) and Power BI DAX calculations allows for a comprehensive sales analysis.
## Key findings include:
✅ Peak sales in January and December, with a decline in February-May.

✅ Weekday 2 has the highest sales, while Weekday 3 is the lowest.

✅ New Zealand and the USA lead in sales, while Canada and the UK underperform.

✅ 50% Dark Bites is the best-selling product, while Almond Choco is the lowest.

✅ Dennison Crosswaite is the top-performing salesperson, while Gunar Cockshoot lags.

✅ APAC region contributes the largest share of sales, while Europe has the lowest.
________________________________________
## Recommendations:
1.	Boost Sales in Off-Peak Months – Introduce seasonal discounts and promotional campaigns to drive sales between February and June.
2.	Expand Marketing in Low-Performing Regions – Implement region-specific strategies for Canada and the UK.
3.	Optimize Product Portfolio – Increase marketing efforts for low-performing products like Almond Choco and Eclairs.
4.	Salesperson Training & Incentives – Provide additional training and motivation for underperforming sales representatives.
5.	Adjust Weekly Sales Strategies – Focus more promotions on weekdays with historically lower sales.
6.	Improve Data Integration & Reporting – Continue leveraging Oracle SQL for structured queries and Power BI DAX for advanced analytics to refine decision-making processes.
7.	Enhance Customer Segmentation – Use predictive analytics to segment customers based on purchasing behavior and tailor promotions accordingly.
8.	Strengthen Forecasting Models – Utilize machine learning techniques to predict future sales trends and optimize inventory management.


________________________________________
