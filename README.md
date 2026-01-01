# Online-Retail-Sales-Performance-Dashboard
A comprehensive Power BI dashboard built from the UCI Online Retail II dataset, providing executive overview, operational analysis, and strategic customer insights.

**Dataset Period**: December 2009 – December 2011  
**Total Revenue Analyzed**: £20.5 million

## Dashboard Overview

### Page 1: Overview – Simple Metrics
- Key KPIs: Total Revenue, Orders, AOV (£510), Unique Customers, Items Sold
- Monthly revenue trend with clear Christmas seasonality
- Revenue by country (bar + interactive map)

<div>
  <img src="https://raw.githubusercontent.com/frankraDIUM/Online-Retail-Sales-Performance-Dashboard/refs/heads/main/1.JPG"/>
</div>

### Page 2: Analysis – Intermediate Metrics
- UK vs International revenue split (86% UK)
- Top 10 bestselling products (cleaned – excludes manual adjustments)
- Customer type breakdown (Registered vs Anonymous)
- AOV trend and detailed country performance table

<div>
  <img src="https://raw.githubusercontent.com/frankraDIUM/Online-Retail-Sales-Performance-Dashboard/refs/heads/main/2.JPG"/>
</div>

### Page 3: Insights – Advanced Metrics
- Customer retention: 28% one-time buyers
- Pareto analysis: Top 20% of customers (~1,175) generate ~65–70% of revenue
- First-Time vs Repeat revenue trends over time
- Monthly revenue with YoY growth visualization

<div>
  <img src="https://raw.githubusercontent.com/frankraDIUM/Online-Retail-Sales-Performance-Dashboard/refs/heads/main/3.JPG"/>
</div>

### Interactive Features
- Year slicers across all pages
- Drill-through pages:
  - Country Details (revenue, trend, top products & customers)
  - Product Details (sales trend, countries, top buyers)

## Key Business Insights

- Strong Christmas seasonality – critical for inventory planning
- UK dominates (~85% revenue), but international markets show higher AOV (growth opportunity)
- Classic Pareto effect: small group of loyal customers drives majority revenue
- Repeat customers fuel long-term growth and seasonal peaks
- Core product focus: gift/home decor items (cakestands, t-light holders, bunting)

## Files Included

- `Online Retail Sales Dashboard.pbix` – Complete Power BI file
- Screenshots of all pages in `/screenshots`
- Dataset in `/data` (original Excel file)

## How to Use

1. Download the repository
2. Open the `.pbix` file in Power BI Desktop (latest version recommended)
3. Explore the three main pages
4. Right-click countries/products for drill-through details

## Data Source

UCI Machine Learning Repository - Online Retail II Dataset  
https://archive.ics.uci.edu/ml/datasets/Online+Retail+II

---

Built with Power BI Desktop – professional-grade retail analytics from raw transactional data.
