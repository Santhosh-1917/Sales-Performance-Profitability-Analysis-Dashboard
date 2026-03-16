# Sales Performance & Profitability Analysis Dashboard

## Overview
This project presents an interactive Tableau dashboard analyzing global sales performance, profitability, and the impact of discount strategies across regions and product categories.

The goal of this dashboard is to help identify key drivers of revenue, understand variations in profitability, and highlight areas where pricing strategies may be affecting business performance.

Key business questions addressed:

- Which regions generate the highest sales and profit?
- Which product categories contribute the most revenue?
- How do discounts influence profitability?
- Which sub-categories are causing losses?

---

## Tools & Technologies

- Tableau
- Data Visualization
- Business Analytics

---

## Dashboard Structure

The dashboard is organized into four main analytical views.

---

## 1. Executive Overview

![Executive Overview](images/Executive%20Summary.png)

This dashboard provides a high-level summary of business performance.

### Key Metrics
- Total Sales: $12.6M  
- Total Profit: $1.46M  
- Profit Margin: 11.61%  
- Total Orders: 25,035  

### Visualizations
- **Sales & Profit Trend**
  - Shows monthly changes in sales and profit.
  - Helps identify seasonal patterns and growth trends.

- **Regional Performance**
  - Compares sales across regions.
  - Highlights which markets contribute most to revenue.

- **Product Category Performance**
  - Compares major categories including Technology, Furniture, and Office Supplies.

This view gives a quick understanding of overall business performance.

---

## 2. Performance Drivers

![Performance Drivers](images/Performance%20Drivers.png)

This dashboard analyzes the factors influencing sales and profitability.

### Sales vs Profit Margin (Country Level)

A scatter plot shows the relationship between log sales and profit ratio.  
Each point represents a country and the size represents the sales volume.

The chart is divided into four quadrants based on average sales and average profit margin.

- **Top Right Quadrant**
  - High sales and high profit margin
  - Includes markets such as the United States and several European and Asian countries.

- **Bottom Right Quadrant**
  - High sales but lower profit margins
  - Suggests that discounting may be affecting profitability.

- **Bottom Left Quadrant**
  - Low sales and low margins
  - These regions contribute less to overall revenue.

- **Top Left Quadrant**
  - Lower sales but relatively strong margins.

Filtering by region reveals additional insights:

- **Africa and EMEA**
  - Maintain reasonable profit margins despite relatively higher discounts.

- **North Asia and Central Asia**
  - Show strong profit margins with comparatively lower discount levels.

---

### Sales Contribution by Sub-Category

The treemap visualization shows how different product sub-categories contribute to total sales.

Key observations:

- Phones and Copiers generate the largest share of revenue.
- Chairs and Bookcases also contribute significantly.
- Profitability varies across categories.

---

### Discount vs Profit Margin by Sub-Category

This scatter plot shows the relationship between average discount and profit margin.

A negative relationship can be observed:

- Higher discounts generally reduce profit margins.
- Categories with moderate discounts maintain positive margins.
- Tables stands out as an outlier with both high discounts and negative profit margin.

---

## 3. Operational Analysis

![Operational Analysis](images/Operational%20Analysis.png)

This dashboard focuses on operational performance across products and regions.

### Bottom Performing Sub-Categories

Identifies products generating the lowest profit, including:

- Tables
- Fasteners
- Labels

These categories may require pricing adjustments or operational improvements.

---

### Top Performing Sub-Categories

The highest profit-generating products include:

- Copiers
- Phones
- Bookcases
- Appliances

These products are the strongest contributors to profitability.

---

### Region Category Table

Provides a detailed breakdown of performance by region and product category, allowing deeper investigation of regional differences.

---

### Monthly Profit Trend

Displays profit changes across months and across different customer segments:

- Consumer
- Corporate
- Home Office

This helps identify seasonal patterns and segment-level performance.

---

## 4. Insights & Recommendations

![Insights and Recommendations](images/Insights%20%26%20Recommendations.png)

### Key Insights

- Higher discounts are linked to lower profit margins.
- Discount levels above 30% drive significant losses.
- Tables is the lowest-performing sub-category with negative profitability.

### Recommended Actions

- Implement approval controls for discounts above 20%.
- Avoid discounts above 30% unless necessary.
- Revisit pricing strategies for Tables and other low-profit sub-categories.

---

## Conclusion

This dashboard demonstrates how interactive visualization can support business decision-making by identifying performance trends, uncovering profitability drivers, and highlighting operational inefficiencies.

Key takeaways:

- A small number of product categories drive most of the revenue.
- Discount strategies significantly affect profitability.
- Certain sub-categories require pricing adjustments to prevent losses.

By combining regional, product-level, and discount analysis, this dashboard provides a comprehensive view of sales performance and profitability drivers.
