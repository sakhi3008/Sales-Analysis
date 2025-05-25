# Sales-Analysis
# 🧭 Purpose of the Project
The goal of this project is to analyze sales and financial data to generate actionable business insights that support strategic decision-making. By exploring key performance indicators (KPIs) such as revenue trends, profitability, customer behavior, and discount impacts, the dashboard enables stakeholders to identify growth opportunities, control expenses, and optimize financial performance.

# 🛠️ Tool Used
Microsoft Excel: For data cleaning, pivot tables, dynamic dashboard creation, financial formulas, and data visualization.

# 📈 Key Concepts Applied
**Total Sales:** Measures total revenue from transactions.

**Total Profit:** Difference between revenue and cost; shows business health.

**Profit Margin:** Profit as a percentage of sales, used to assess efficiency.

**Discount Impact:** Analyzed how discounts affect both sales volume and profit.

**Customer Segmentation:** Identified top and bottom performing customers.

**Year-over-Year (YoY) Comparison:** Compared revenue and profit across different years.

**Trend Analysis:** Used line charts to understand seasonal or monthly patterns.

**KPI Cards:** Highlighted current performance metrics such as Total Sales, Profit, and Discount %.

# ⌐ DAX Measures and Calculated Columns

Several custom DAX measures were created to provide enhanced insights:

**Total Sales** = SUM(Sales[Sales Amount])

**Total Profit** = SUM(Sales[Profit])

**Discount %** = DIVIDE(SUM(Sales[Discount Amount]), SUM(Sales[Sales Amount]))

**Profit Margin** = DIVIDE([Total Profit], [Total Sales])

**YoY Sales Growth** = ([Current Year Sales] - [Previous Year Sales]) / [Previous Year Sales]

Additional time intelligence functions were used to evaluate YoY comparisons and month-to-date trends.

# 📌 Project Contributions & Deliverables
✔️ **Data Cleaning & Preparation:**

Removed inconsistencies and structured raw data using Excel formulas and manual checks.

✔️ **Dashboard Creation:**

Built a fully interactive and visually clean Excel dashboard.

Included slicers for month, year, and product filters.

Used Pivot Tables and Pivot Charts for dynamic updates.

✔️ **Financial Analysis:**

Created calculated fields for key financial ratios (Gross Margin %, Net Margin %, etc.).

Highlighted peak and low-performance months for better decision-making.


# 📌 Insights & Recommendations

- High Discounts → Lower Profitability

Excessive discounting often led to reduced margins without a proportional increase in sales volume.

- Top 10 Customers = Majority of Revenue
  
A small group of customers contributed the majority of total revenue, suggesting the need for loyalty initiatives or premium services.

- Seasonal Sales Trends Identified
  
Specific months showed consistently higher sales, hinting at marketing opportunities during those periods.

- Unprofitable Products Detected
  
Some products sold in high volume but had very low or negative profit margins. These may need price adjustment or bundling strategies.

- Regional Disparities in Sales
  
Sales were concentrated in certain regions, indicating opportunities to expand or replicate success in underperforming regions.

# 📌 Files Included
## Sales Report 
- [Customer Performance Report](https://github.com/sakhi3008/Sales-Analysis/blob/main/Customer%20Performance%20Report.pdf)
- [Market Performance Report](https://github.com/sakhi3008/Sales-Analysis/blob/main/Market%20Performance%20Report.pdf)
- [Top 10 products](https://github.com/sakhi3008/Sales-Analysis/blob/main/Top%2010%20products.pdf)
- [Division level report](https://github.com/sakhi3008/Sales-Analysis/blob/main/Division%20level%20report.pdf)
- [Top & Bottom 5 Products](https://github.com/sakhi3008/Sales-Analysis/blob/main/Top%20%26%20Bottom%205%20Products.pdf)
- [New Products - 2021](https://github.com/sakhi3008/Sales-Analysis/blob/main/New%20Products%20-%202021.pdf)
- [Top 5 Countries](https://github.com/sakhi3008/Sales-Analysis/blob/main/Top%205%20Countries.pdf)

## Finance Report 
- [P & L Year](https://github.com/sakhi3008/Sales-Analysis/blob/main/P%20%26%20L%20Year.pdf)
- [P & L by Month](https://github.com/sakhi3008/Sales-Analysis/blob/main/P%20%26%20L%20by%20Month.jpg)
- [P & L Markets](https://github.com/sakhi3008/Sales-Analysis/blob/main/P%20%26%20L%20Markets.pdf)
- [GM% by Quarters(Sub Zone)](https://github.com/sakhi3008/Sales-Analysis/blob/main/GM%25%20by%20Quarters(Sub%20Zone).pdf)



