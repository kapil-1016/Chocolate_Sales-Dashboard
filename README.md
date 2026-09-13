## 🍫 Awesome Chocolates: Global Sales Performance Dashboard

An interactive Power BI dashboard built to track and analyze chocolate sales performance across countries, products, and sales representatives — covering revenue, shipments, cost, and profitability in one view.

## Purpose
The Awesome Chocolates Dashboard is a visually rich, interactive Power BI report designed to help stakeholders monitor sales performance for a chocolate manufacturing and distribution business operating across 6 countries (Australia, Canada, India, New Zealand, UK, USA). The dashboard tracks sales, boxes shipped, shipment counts, cost, profit, and profit percentage, while also ranking individual sales representatives by performance. It is built for sales managers, regional heads, and business analysts who need to quickly spot top performers, underperforming regions, and month-over-month trends.

## Tech Stack
The dashboard was built using the following tools and technologies:\
- **📊 Power BI Desktop -** Main data visualization and reporting platform.
- **📂 Power Query —** Used to clean and transform raw sales data (handling nulls, splitting columns, standardizing product categories).
- **🧠 DAX (Data Analysis Expressions) —** Used to build measures such as MoM % change, Profit %, Lbs %, and the overall profit-percentage gauge.
- **📝 Data Modeling —** Relationships built between sales, product, and geography tables to support cross-filtering by country and product category.
## Data Sources
Source: Kaggle — "Awesome Chocolates Sales Data" dataset.\
The dataset contains transactional sales records for a chocolate company, including fields such as sales person, country, product category (Bars, Bites, Other), amount, boxes shipped, cost, and profit. It is a widely used practice dataset on Kaggle for building Power BI/Excel sales dashboards.

## Business Problem

Sales leadership across multiple countries and product lines struggled to get a single, consistent view of performance. Questions such as:\
- Which sales reps are driving the most profit, not just the most sales?\
- Which countries or product categories are underperforming month-over-month?\
- How efficiently is product being shipped relative to boxes sold?\

...were hard to answer from raw spreadsheet exports.

## Goal of the Dashboard
To deliver an interactive tool that:\

- Lets users filter performance by product category (Bars, Bites, Other) and by country.
- Surfaces month-over-month (MoM) movement on every core KPI.
- Ranks sales representatives by sales, profit, and profit % with a quick pass/fail performance flag.
- Highlights shipment efficiency and pounds-shipped-per-box trends.

## Walkthrough of Key Visuals

- **Key KPI Cards (Top Row)** Total Sales: **3M** (MoM -35.3%) · Total Boxes: **167K** (MoM -0.15) · Total Shipments: **504** (MoM -0.28) · Total Cost: **1.05M** (MoM -0.29) · Total Profit: **2M** (MoM -0.39) · Profit %: **63.66%** gauge.
- **Category Filter Panel (Left)** A slicer lets users filter every visual by product category — Bars, Bites, or Other.
- **Country Filter Panel (Left)** A second slicer filters the whole report by country: Australia, Canada, India, New Zealand, UK, USA.
- **Metric Tab Selector** Tabs (Sales, Boxes, Shipments, Cost, Profit, Profit_Per) let users swap the main trend chart between different KPIs without leaving the page.
- **Sales by Start of Month (Line Chart)** Tracks total sales trend month-over-month from early 2023 into 2024, making seasonal spikes and dips easy to spot.
- **Total Shipments by Boxes — Bins (Histogram)** A binned histogram with a range slider showing the distribution of shipment sizes, helping identify typical order volumes.
- **Lbs% Gauge** A small gauge (currently 8%) showing pounds shipped as a percentage of a target, used as a quick efficiency indicator.
- **Sales Person Leaderboard (Table)** Ranks every sales rep by Sales, Profit, and Profit %, with a Lbs% column and a green/red status icon flagging whether each rep is hitting their performance target.

## Business Impact & Insights

- **Performance Management:** Managers can instantly identify top and bottom sales reps by profit %, not just raw sales volume.
- **Regional Strategy:** Country-level filtering reveals which markets are growing or declining month-over-month.
- **Product Mix Optimization:** Category filters (Bars, Bites, Other) show which product lines drive the most profit per box shipped.
- **Operational Efficiency:** The shipment histogram and Lbs% gauge help flag inefficient shipping patterns early.
