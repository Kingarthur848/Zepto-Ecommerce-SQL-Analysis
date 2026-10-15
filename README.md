 Zepto E-commerce SQL Data Analysis

 Project Overview
This project analyzes Zepto's product inventory and pricing data using SQL and PostgreSQL. The objective is to understand product availability, discount strategies, category-level pricing, and inventory value to derive actionable business insights.

 Objectives
- Clean and validate raw product data.
- Analyze product pricing, MRP, and discount percentages.
- Identify out-of-stock products and high-discount items.
- Compare average discounts across product categories.
- Estimate inventory value and analyze product weight segments.
- Generate insights to support pricing and inventory decisions.

 Dataset
The dataset contains 3,732 product records and 9 columns, representing product SKUs scraped from Zepto listings.

Key columns include:
- `Category` – Product category
- `name` – Product name
- `mrp` – Maximum Retail Price
- `discountPercent` – Discount percentage
- `availableQuantity` – Available inventory quantity
- `discountedSellingPrice` – Discounted selling price
- `weightInGms` – Product weight in grams
- `outOfStock` – Product availability status
- `quantity` – Product quantity or pack information

 Tools & Technologies
- PostgreSQL – Data querying and analysis
- SQL – Data cleaning, aggregation, filtering, and business analysis
- CSV – Dataset storage and import

 Data Cleaning & Preparation
- Checked for missing values and duplicate records.
- Identified and removed records with zero MRP where appropriate.
- Converted MRP and discounted selling prices from paise to rupees.
- Validated product availability and pricing fields.
- Prepared the dataset for reliable analysis.

 Business Questions Explored
1. Which products offer the highest discounts?
2. Which high-priced products are out of stock?
3. Which categories have the highest average discounts?
4. What is the estimated inventory value by product category?
5. Which expensive products have relatively low discounts?
6. How does price per gram vary across products?
7. How can products be segmented by weight?
8. Which categories hold the greatest inventory weight?

 Key Findings
- The dataset contained 3,200 in-stock and 453 out-of-stock product records after the applied cleaning steps.
- Several products offered discounts of 50% or more.
- Fruits and vegetables had an average discount of approximately 15% in the analyzed data.
- Category-level pricing and inventory analysis helped identify opportunities for better stock management and pricing decisions.

Note: Findings reflect the analyzed dataset and may change with updated product listings.

 SQL Concepts Demonstrated
- SELECT, WHERE, ORDER BY
- Aggregate functions: SUM, AVG, COUNT
- GROUP BY and HAVING
- CASE statements
- Subqueries and Common Table Expressions (CTEs)
- Window functions
- Data cleaning and type validation
- Business-oriented analytical queries

 Repository Structure
```text
Zepto-Ecommerce-SQL-Analysis/
├── zepto_customer_analysis.sql
├── zepto_v2.csv
└── README.md
```

 How to Run
1. Clone or download this repository.
2. Create a PostgreSQL database.
3. Import `zepto_v2.csv` into a table with appropriate data types.
4. Review the table and column names in the SQL script.
5. Execute `zepto_customer_analysis.sql` using PostgreSQL or pgAdmin.
6. Review the query results to explore the business insights.

 Conclusion
This project demonstrates the use of SQL to transform raw e-commerce product data into meaningful business insights. It showcases practical skills in data cleaning, pricing analysis, inventory evaluation, and business problem-solving.

 Author
Kshitij Bisht

Aspiring Data Analyst | SQL | Excel | Power BI | Python
