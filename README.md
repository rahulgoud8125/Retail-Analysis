# 📊 Retail Business Performance & Profitability Analysis
**📌 Project Overview**

This project analyzes retail transactional data to evaluate business performance, identify profit-draining categories, detect slow-moving products, and understand seasonal sales behavior. The analysis supports data-driven decisions for inventory optimization and profitability improvement.

**🎯 Objectives**

Analyze overall sales and profitability performance

Identify high-performing and loss-making product categories

Detect slow-moving products using sales quantity metrics

Understand seasonal and time-based sales patterns

Compare weekday vs weekend customer behavior

Provide actionable business recommendations

**🗂 Dataset Description**

The dataset contains product-level monthly sales information, including:

Product details (product_id, product_category_name)

Sales metrics (qty, unit_price, total_price)

Customer indicators (customers)

Time attributes (month, year, weekday, weekend, holiday)

Pricing history (lag_price)

Note: Profit is calculated using an assumed cost based on lag price due to the absence of actual cost data.

**🧮 Key Measures & Calculations**

The following measures were created in Power BI using DAX:

Total Sales

Total Quantity

Total Profit (Derived)

Profit Margin (%)

Quantity per Customer

Season Classification

Weekday vs Weekend Sales

**📊 Dashboard Structure**

KPI Cards for Sales, Profit, Quantity, and Margin

Category-wise Sales vs Profit comparison

Time-based trend analysis

Interactive filters for Year, Season, and Category

Identification of slow-moving products using low quantity sales

Category-level performance comparison

Product-level action table with conditional formatting

Monthly sales trends by category

Season-wise sales contribution

Weekday vs Weekend sales comparison

**🔍 Key Insights**

Certain product categories generate high sales but low profit margins

Multiple products exhibit consistently low sales quantities, indicating slow movement

Seasonal demand variations significantly impact category performance

Weekday sales generally outperform weekend sales, suggesting business-driven demand
