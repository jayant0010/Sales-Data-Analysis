# Sales Data Analysis - Adventure Works Overview

## Project Description:
This project focuses on analyzing the sales performance of Adventure Works across different continents and product categories. The goal is to provide a comprehensive overview of total sales, track progress toward sales targets, and identify margin performance by product category. The data is visualized in a Power BI dashboard with key metrics such as total sales, sales performance over time, and margin distribution.

## Dashboard Features:
1. **Total Sales Overview**: 
   - **Total Sales**: $9.81M
   - **Target**: $7M
   - This metric allows tracking the sales performance against a set target.

2. **Sales Performance Over Time**:
   - A line graph representing monthly sales from January to December 2021.
   - Shows a sharp upward trend toward the end of the year, with sales peaking in December at approximately $1.6M.

3. **Sales by Continent**:
   - Bar chart displaying total sales across different continents: Australia ($7.8M), Europe ($8.2M), and North America ($10.1M).
   - North America leads the sales, followed closely by Europe.

4. **Margin % by Product Category**:
   - Bar chart illustrating margin percentages for different product categories: Accessories, Bikes, and Clothing.
   - Accessories show the highest margin, followed by Bikes and Clothing.

5. **Filters**:
   - Continent and Year filters to allow users to dynamically view sales and margins by geographical regions and time frames.

## Data Model:
The data model consists of the following key entities:
1. **Customer Table**: Contains customer demographic details such as country, city, income, and marital status.
2. **Sales Table**: Stores transactional sales data, including customer details, product details, sales amount, and quantity.
3. **Order Date Table**: Provides order date hierarchy information, breaking down sales over time.
4. **Product Table**: Contains product-specific information, such as category, subcategory, and product name.
5. **Sales Territory Table**: Represents sales distribution across different geographic territories, including continents and regions.

The tables are connected through foreign keys, ensuring proper relational data structure. The key relationships are:
- **Customer Key** connects the Sales and Customer tables.
- **Product Key** connects the Sales and Product tables.
- **Order Date Key** connects the Sales and Order Date tables.
- **Sales Territory Key** connects the Sales and Sales Territory tables.

## Insights:
- **Total Sales** exceed the target by approximately 40%, demonstrating strong sales performance.
- **North America** leads in sales volume, followed by Europe and Australia.
- **Accessories** provide the highest margin percentage, indicating higher profitability in this product category.
- Sales performance sees a steady rise over the year, with a significant spike toward the end, likely due to seasonal factors.

## Conclusion:
The dashboard provides a user-friendly interface for visualizing the overall sales performance of Adventure Works. It is instrumental in tracking the progress toward sales targets and identifying high-margin product categories and strong geographic markets.

## Credits:

data sourced from:
https://learn.microsoft.com/en-us/power-bi/create-reports/desktop-dimensional-model-report

https://www.linkedin.com/learning-login/share?forceAccount=false&redirect=https%3A%2F%2Fwww.linkedin.com%2Flearning%2Fcomplete-guide-to-power-bi-for-data-analysts-by-microsoft-press%3Ftrk%3Dshare_ent_url%26shareId%3DYS%252FSSN9tSpWP7%252B%252FHbLO%252Bog%253D%253D



