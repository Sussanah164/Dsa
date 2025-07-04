# Amazon Product Review Analysis (My DSA Incubator Project)
In my project at DSA Incubator, I developed a comprehensive Excel-based analytics solution to analyze Amazon product reviews, discounts, and pricing. By leveraging pivot tables, slicers, calculated fields, and interactive dashboards, I extracted valuable insights into product performance, category trends, customer engagement, and revenue growth opportunities.

# Objective: **Analyze Amazon product and review data to derive business insights using pivot tables, slicers, calculated columns, and data visualizations.**

# Project Context
* Client Name: RetailTech Insights
* Industry: E-commerce Analytics
* Role: Junior Data Analyst
* Tools Used: Microsoft Excel (Pivot Tables, Charts, Conditional Formatting, Slicers, Cards)

# Dataset Description
* Total Records: 1,465
* Columns: 16
* Source: Web-scraped Amazon product review data
* Each row represents: A unique product
* Fields included:Product name, Category, Actual price & Discounted price, Discount %, Rating,Number of Ratings (Rating Count),Review content (aggregated in some columns) and Revenue potential fields (derived)
# # # Key Analytical Tasks & Solutions|
* 1	What is the average discount % by product category? (Pivot Table + Average Formula)
* 2	How many products are listed under each category?	(Pivot Table + Count)
* 3	What is the total number of reviews per category?	(SUM of Rating Count by category)
* 4	Which products have the highest average ratings?	(Sorting based on calculated Average Rating)
* 5	What is the actual vs discounted price by category?	(Grouped Bar Chart + Pivot Summary)
* 6	Which products have the highest number of reviews?	(Top-N Analysis using Sorting + Pivot Table)
* 7	How many products have ≥ 50% discount?	(Filter logic on Discount column)
* 8	What is the distribution of product ratings (e.g., 3.0, 4.0, etc.)?	(Grouped histogram with Pivot Count)
* 9	Total potential revenue (actual_price × rating_count) per category?	(New Calculated Column + Pivot Table SUM)
* 10	Unique product count per price range bucket (<₹200, ₹200–₹500, >₹500)?	(IF formulas + Donut Chart)
* 11	Relationship between rating and discount level?	(Scatter Line Chart (2 y-axes)
* 12	How many products have fewer than 1,000 reviews?	(COUNTIF Formula + Bar Chart)
* 13	Categories with highest average discount?	(Sorted Pivot Table by Discount%)
* 14	Top 5 products by combined review count and rating	(Ranking logic using SUM(Rating × ReviewCount)

## Analysed Files
https://us.docworkspace.com/d/sIGq69pNT2ZefwwY?sa=601.1037

![image](https://github.com/user-attachments/assets/87665400-a87a-4b0f-92f5-0941a353510a)

![Amazon Data](https://github.com/user-attachments/assets/e37c6a92-cd99-4d78-a089-15ecd6458fac)

![Cleaned](https://github.com/user-attachments/assets/ba4cffde-398a-41f5-83b1-0a543938ff8b)

![image](https://github.com/user-attachments/assets/1cabdc8e-445e-44da-a33f-778a279536eb)

# # Key Highlights from Dashboard:
* Discount vs Rating: Discounted products don’t always have higher ratings. There’s a complex relationship.
* Price Range Bucket: Most products fall under the affordable to moderately expensive range.
* Revenue Potential: Categories like Home Kitchen and Electronics dominate in potential revenue.
* Category-wise Review Count: Electronics and accessories lead in user engagement.
* Top 5 Products: Based on high review count and strong ratings (e.g., AmazonsBasics FI, Realme X, etc.)
* Discount Percentage by Category: Health and home products offered the most generous discounts.
# # Skills & Competencies Demonstrated
    * Skill and	How I Applied It

* Data Cleaning: Removed nulls, corrected inconsistent formats, trimmed text
* Data Aggregation:	Used pivot tables and grouping to summarize key insights
* Excel Formulas:	IF, COUNTIF, AVERAGEIFS, PROPER, calculated columns
* Visualization:	Designed intuitive charts (bar, pie, line, donut, cards)
* Slicers & Cards: Enabled dynamic filtering and KPI display
* Business Reasoning:	Drew conclusions based on data trends and business logic










