🥤 SodaPop Sales Analysis Dashboard
This repository contains the sodapop.pbix project, a comprehensive Power BI Desktop dashboard designed to analyze beverage sales performance, regional trends, and product distribution.

📊 Project Overview
The dashboard transforms raw transactional data into actionable insights for the beverage industry. It focuses on tracking revenue, monitoring profit margins, and identifying growth opportunities across different soda brands and geographic regions.

💡 Key Insights
This dashboard translates complex sales data into the following strategic takeaways:
a] Revenue & Profitability Trends: Identifies top-performing brands and calculates the percentage contribution of each to total revenue.
b] Margin Analysis: Provides a deep dive into product profitability after accounting for unit costs.
c] Regional Market Performance: Uses geographic visuals to identify high-density sales "hotspots" and underperforming territories.
d] Product & Unit Volume: Analyzes consumer preferences between bulk packaging and single-unit purchases.
e] Seasonal Spikes: Tracks sales peaks, such as increased demand during summer months, to assist with inventory and marketing planning.

🛠️ Technical Structure
The project is built using a structured Power BI file format. Based on the internal file components, the project includes:
a] Data Model: The core semantic model containing table relationships and calculations.
b] Report Layout: A custom interface defined by specific layout configurations.
c] Theme Configuration: Utilizes the CY25SU11.json base theme for modern styling and consistent visual branding.
d] Diagram Layout: Includes a visual mapping of the data model schema for easier maintenance.
e] Security Bindings: Features internal security configurations to ensure data integrity.
f] Metadata & Settings: Stores specific project-level settings and versioning information.

🧪 Key DAX Concepts Applied
The report utilizes dynamic DAX (Data Analysis Expressions) to ensure responsive filtering across visuals:
a] Total Revenue: Aggregate sums of sales across the entire dataset.
b] Safety Division: Implementation of the DIVIDE function to prevent errors during margin calculations.
c] Filter Context: Strategic use of CALCULATE to isolate brand performance against regional filters.
