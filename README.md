# samplesalesusingpowerbi

# Sales & Financial Dashboard Project

**Dataset**: *Financial Sample* (Excel workbook used for Power BI)  
**Prepared by**: [Your Name]  
**Date**: [Submission Date]

---

## 🎯 Project Objective  
This interactive dashboard provides business stakeholders with insights into sales performance, profitability, and growth trends across products, regions, and time periods.  
Key goals:  
- Monitor Total Sales, Total Profit, and Margin % over time  
- Compare performance by Product, Country, and Segment  
- Enable interactive filtering to answer business questions like “Which products drive high-profit?”, “Which region under-performs?”, “How are trends evolving month-by-month?”

---

## 📊 Data Source & Model Overview  
- **Dataset Source**: Financial Sample workbook (contains sales, units sold, cost of goods sold (COGS), profit etc.)  
- **Fact Table**: Sales — includes metrics for Sales, Units Sold, COGS, Profit  
- **Dimension Tables**:  
  - Product (product names, categories, discount bands)  
  - Country (geographic data)  
  - Segment (market segment such as Corporate, Government, Channel)  
  - Date (year, month, day)  
- This star-schema model enables slicing and dicing metrics by context (product, region, time, segment).

---

## 📈 Visualisations Included  
1. **Time-Trend Line Chart** — Displays Sales & Profit over time to identify growth, seasonality and dips.  
2. **Bar Chart by Product** — Compares units sold or revenue across different products to spot top-performers and laggards.  
3. **Scatter Plot: Sales vs Profit** — Shows the relationship between high sales and high profit (or low margin) to highlight potential issues.  
4. **Bar Chart by Country/Segment** — Reveals which geographies or segments deliver the best profitability or margin.  
5. **KPI Cards** — Headline metrics like Total Sales, Total Profit and Margin % for quick executive view.  
6. **Interactive Slicers/Filters & Navigation Menu** — Allows users to filter by Year, Country, Product or Segment and navigate between pages (Overview, Sales Detail, Profit Detail).

---

## 🖥️ Dashboard Deployment  
- Built in Power BI Desktop (version [enter version])  
- `.pbix` file included in this repository under `/dashboard` folder.  
- Screenshots of each page in `/screenshots` folder for preview.  
- Use the top navigation buttons inside the report to switch pages: **Overview → Sales Detail → Profit & Margin Detail**.  
- Slicers available on each page for interactive filtering.

---

## 🔍 Insights & Key Findings  
- Sales grew from **[X]** in Year 1 to **[Y]** in Year 2 with a margin improvement of **[Z %]**.  
- Product **[Name]** had the highest units sold, but margin was comparatively low, suggesting cost-efficiency issues.  
- Country **[Name]** shows high revenue but moderate profit, indicating higher COGS or discounts.  
- Segment **[Name]** under-performed; further investigation suggested higher discount bands impacting profitability.

---

## ✔️ Next Steps & Recommendations  
- Introduce **Customer Segment Analysis** to identify high-value customers.  
- Add **Budget vs Actual** and **Forecasting** visuals for future planning.  
- Refresh dataset monthly and publish via Power BI Service with stakeholder access.  
- Investigate cost reduction for high-volume low-margin products.  
- Expand dashboard to include **COGS breakdown**, **Discount Impact**, and **Channel Performance**.

---

## 📂 Repository Structure  
