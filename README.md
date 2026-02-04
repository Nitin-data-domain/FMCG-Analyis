# FMCG Multi-Country Sales Analysis Dashboard | Power BI Project

A comprehensive, interactive Power BI dashboard designed to analyze Fast-Moving Consumer Goods (FMCG) sales performance across multiple countries. This data-driven business intelligence tool provides actionable insights into revenue optimization, profitability analysis, product performance metrics, regional sales trends, and promotional campaign effectiveness to support strategic business decisions in the FMCG industry.

## Project Overview and Purpose

The FMCG Multi-Country Sales Analysis Dashboard is an end-to-end business intelligence solution built to help stakeholders across sales, marketing, and finance teams analyze and optimize FMCG operations. This Power BI dashboard consolidates sales data from multiple countries and provides deep insights into financial performance, product categories, brand performance, regional distribution, and the impact of promotional activities. 

This analytical tool is designed for business analysts, product managers, sales directors, marketing teams, and C-suite executives seeking to make data-driven decisions in the competitive FMCG industry. The dashboard enables users to track key performance indicators (KPIs), identify sales trends, compare regional performance, and evaluate promotional campaign ROI.

## Technology Stack and Tools

The dashboard was built using the following Microsoft Power BI technologies and data analytics tools:

**Power BI Desktop** - Main data visualization platform for creating interactive reports and dashboards with dynamic visuals and cross-filtering capabilities

**Power Query** - ETL (Extract, Transform, Load) tool for data transformation, cleaning, and preparation layer ensuring data quality and consistency

**DAX (Data Analysis Expressions)** - Custom measures, calculated columns, KPIs, time intelligence functions, and advanced analytics for business metrics

**Data Modeling** - Star schema implementation with established relationships between fact and dimension tables for optimal query performance and scalability

**File Format** - .pbix format for Power BI Desktop development, .png format for dashboard previews and documentation

## Data Source and Dataset Information

**Primary Data Source:** FMCG Multi-Country Sales Dataset from Kaggle

**Dataset Link:** https://www.kaggle.com/datasets/robertocarlost/fmcg-multi-country-sales-dataset/code

The dataset contains comprehensive sales transaction data for FMCG products across multiple countries and regions. Key data elements include:

- Sales transactions with revenue, quantity, and units sold metrics
- Product information including categories, brands, SKUs, and product attributes
- Geographic dimensions with country, region, and city-level data
- Promotional data including discount percentages and campaign information
- Financial metrics such as profit, cost of goods sold (COGS), and margin calculations
- Time-series data spanning multiple years for historical trend analysis and forecasting
- Customer segment information for demographic analysis

## Business Problem Statement

The Fast-Moving Consumer Goods industry is characterized by intense competition, razor-thin profit margins, rapid inventory turnover, and diverse product portfolios spanning multiple categories and brands. FMCG companies face several critical analytical challenges:

**Revenue Optimization Challenges:** Understanding which product categories and brands generate the highest revenue across different geographic markets and customer segments

**Profitability Analysis Needs:** Identifying which products, regions, and promotional strategies deliver the best profit margins while balancing volume and value growth

**Regional Performance Gaps:** Determining which countries and regions drive the most revenue and profit, and why certain markets underperform relative to their potential

**Promotional Effectiveness Questions:** Measuring the true impact of promotional campaigns on sales volume, revenue, and profitability to optimize marketing spend

**Product Portfolio Management:** Deciding which products to invest in, which to maintain, and which to phase out based on performance metrics

**Inventory and Supply Chain Planning:** Forecasting demand patterns to prevent stockouts in high-demand regions while minimizing excess inventory

Without a unified analytical view and interactive business intelligence dashboard, decision-makers struggle to identify growth opportunities, optimize inventory management, allocate marketing budgets effectively, and respond quickly to market changes.

## Dashboard Goals and Objectives

The FMCG Multi-Country Sales Analysis Dashboard was designed to achieve the following strategic objectives:

**Enable Real-Time Performance Monitoring:** Provide stakeholders with instant access to key financial and sales metrics for quick decision-making

**Support Strategic Business Decisions:** Empower leaders to make informed choices around product portfolio management, regional expansion strategies, promotional planning, and pricing optimization

**Uncover Actionable Business Insights:** Reveal hidden patterns in revenue drivers, profitability trends, customer behavior, and market dynamics through visual analytics

**Facilitate Cross-Functional Collaboration:** Create a common analytical framework for data-driven discussions across Sales, Marketing, Finance, and Operations teams

**Improve Forecasting Accuracy:** Leverage historical trends and seasonality patterns to develop more accurate sales forecasts and demand predictions

**Optimize Resource Allocation:** Help managers allocate resources (budget, inventory, personnel) to the highest-impact opportunities

## Dashboard Visualizations and Screenshots

![FMCG Sales Analysis Dashboard - Overview Page](https://github.com/Nitin-data-domain/FMCG-Analyis/blob/main/Images/FMCG-1.jpeg)

![FMCG Sales Analysis Dashboard - Product Performance Page](https://github.com/Nitin-data-domain/FMCG-Analyis/blob/main/Images/FMCG-2.jpeg)

![FMCG Sales Analysis Dashboard - Regional Analysis Page](https://github.com/Nitin-data-domain/FMCG-Analyis/blob/main/Images/FMCG-3.jpeg)

## Key Performance Indicators and Metrics

The dashboard prominently displays critical business metrics that provide an instant health check of FMCG business performance:

**Total Revenue** - Aggregate sales value generated across all products, regions, and time periods

**Total Profit** - Net profitability after deducting cost of goods sold and operational expenses

**Profit Margin Percentage** - Profitability ratio calculated as (Profit / Revenue) x 100 to assess efficiency and pricing effectiveness

**Units Sold** - Total volume of products sold across all categories and SKUs

**Average Transaction Value** - Mean revenue per transaction calculated as Total Revenue / Number of Transactions

**Number of Products and Brands** - Portfolio diversity metrics showing breadth of product offerings

**Year-over-Year Growth** - Percentage change in key metrics compared to the previous year

**Market Share by Region** - Relative performance across different geographic markets

These KPIs provide stakeholders with an immediate understanding of business performance and establish baselines for goal-setting and performance tracking.

## Regional Performance Analysis and Geographic Insights

**Visualization Types:** Interactive maps, geographical distribution charts, heat maps, and regional comparison tables

The regional performance section displays FMCG sales metrics across different countries, regions, and cities using:

**Geographic Heat Maps** - Visual representation of sales concentration and revenue density across territories

**Country-Level Comparisons** - Bar charts ranking countries by revenue, profit, units sold, and market penetration

**Regional Drill-Down Capability** - Interactive filtering from continent to country to region to city level for granular analysis

**Market Penetration Metrics** - Percentage of total addressable market captured in each region

**Growth Rate Analysis** - YoY and MoM growth rates by geography to identify emerging and declining markets

**Business Value and Applications:**

Sales teams can prioritize high-potential regions for field expansion and resource allocation. Marketing teams can customize campaigns based on regional preferences and purchasing behaviors. Supply chain managers can optimize distribution networks and inventory placement based on regional demand patterns. Strategy teams can identify expansion opportunities in underserved markets with favorable demographics.

## Product Category and Brand Performance Analysis

**Visualization Types:** Stacked bar charts, clustered column charts, treemaps, and product mix analysis

This section provides comprehensive analysis of product portfolio performance:

**Category-Level Revenue Comparison** - Compares sales performance across major product categories such as Beverages, Snacks, Dairy Products, Personal Care, and Household Items

**Brand Performance Rankings** - Identifies top-performing and underperforming brands within each category based on revenue, profit, and volume metrics

**Product Mix Distribution** - Shows percentage contribution of each category to total revenue and profit

**SKU-Level Performance** - Detailed analysis of individual product performance for inventory optimization

**New Product Performance Tracking** - Monitors adoption rates and sales velocity of newly launched products

**Cross-Sell and Bundle Analysis** - Identifies products frequently purchased together for merchandising opportunities

**Business Value and Applications:**

Product managers can identify star products deserving of increased marketing investment and shelf space. Category managers can optimize product assortment and discontinue underperforming SKUs to reduce complexity. Procurement teams can negotiate better terms with suppliers of high-volume products. Innovation teams can identify white spaces and opportunities for new product development.

## Sales Trends and Time-Series Analysis

**Visualization Types:** Line charts, area charts, trend lines, and time-series decomposition

The temporal analysis section tracks FMCG sales performance over time to reveal patterns and trends:

**Revenue and Profit Trends** - Monthly, quarterly, and annual trends with moving averages and trend lines

**Seasonality Pattern Identification** - Highlights recurring patterns tied to holidays, seasons, or promotional calendars

**Year-over-Year Comparisons** - Side-by-side comparison of current period vs. same period last year

**Growth Rate Calculations** - Month-over-month and year-over-year percentage changes in key metrics

**Sales Velocity Metrics** - Rate of sales over time to identify accelerating or decelerating products

**Forecast Projections** - Predictive analytics showing expected future performance based on historical patterns

**Business Value and Applications:**

Finance teams can develop accurate budgets and financial forecasts based on historical trends and seasonality. Operations teams can plan production schedules and inventory builds for peak seasons. Marketing teams can time promotional campaigns to coincide with or counteract seasonal patterns. Executive teams can set realistic growth targets informed by historical performance.

## Promotional Campaign Impact Analysis

**Visualization Types:** Comparison charts, before-and-after analysis, lift analysis, and ROI calculations

This critical section measures the effectiveness of promotional activities:

**Promoted vs. Non-Promoted Sales** - Compares revenue and volume during promotional periods vs. baseline periods

**Discount Impact Analysis** - Shows relationship between discount depth and sales lift, profit erosion

**Promotional Lift Metrics** - Calculates percentage increase in sales attributable to promotions

**ROI of Marketing Campaigns** - Measures incremental profit generated per dollar of promotional spending

**Channel-Specific Promotion Performance** - Analyzes which channels (online, retail, wholesale) respond best to promotions

**Customer Response Analysis** - Segments customers by promotional sensitivity and deal-seeking behavior

**Long-Term Impact Assessment** - Evaluates whether promotions steal from future sales or create lasting demand

**Business Value and Applications:**

Marketing teams can optimize promotional strategies by identifying which tactics drive volume without destroying margins. Pricing teams can set optimal discount levels that maximize profitability. Sales teams can negotiate better trade promotion terms with retailers based on proven ROI. Finance teams can accurately budget promotional spending and forecast its impact on quarterly results.

## Profitability Analysis and Margin Management

**Visualization Types:** Waterfall charts, margin bridges, contribution analysis, and profit decomposition

The profitability section breaks down profit drivers and identifies optimization opportunities:

**Margin Analysis by Dimension** - Profit margins segmented by product category, brand, region, and customer segment

**Cost Structure Breakdown** - Separates fixed costs from variable costs and COGS from operational expenses

**Price-Volume-Mix Analysis** - Decomposes profit changes into contributions from pricing, volume, and product mix shifts

**Contribution Margin Analysis** - Shows which products and regions contribute most to covering fixed costs

**Margin Compression Identification** - Highlights areas where margins are declining and requires intervention

**What-If Scenario Modeling** - Allows users to model impact of price changes, cost reductions, or mix shifts

**Business Value and Applications:**

Finance teams can develop strategies to improve overall company profitability and EBITDA margins. Pricing teams can identify opportunities for selective price increases in less price-sensitive segments. Procurement teams can prioritize cost reduction initiatives in high-impact categories. Sales teams can focus on selling higher-margin products and avoid over-discounting.

## Interactive Filters and Dynamic Slicers

The dashboard includes comprehensive filtering capabilities for customized analysis:

**Geographic Filters** - Country, Region, City selection for location-based analysis

**Product Dimension Filters** - Category, Brand, SKU selection for product-focused analysis

**Time Period Slicers** - Date range, Month, Quarter, Year selection for temporal analysis

**Promotional Status Filter** - Toggle between promoted and non-promoted periods

**Customer Segment Filters** - B2B, B2C, wholesale, retail channel selection

**Performance Thresholds** - Filter for top/bottom performers, high/low margin products

**Business Value:** Users can customize dashboard views based on specific analytical needs without creating multiple static reports, enabling self-service analytics and reducing dependency on IT or analytics teams.

## Business Impact and Strategic Insights

### Marketing Optimization and Campaign Management

Identify which promotional tactics and marketing channels yield the highest return on investment (ROI). Allocate marketing budgets to high-performing regions, products, and customer segments. Tailor campaign messaging and creative based on regional preferences and demonstrated purchasing behaviors. Optimize promotional timing to align with natural demand patterns. Reduce wasteful spending on ineffective promotional activities.

### Strategic Market Expansion and Geographic Growth

Discover underserved markets with favorable demographics and growth potential. Benchmark performance across similar regions to set realistic targets and identify best practices. Plan geographic expansion and distribution network development based on data-driven market assessments. Prioritize investment in high-potential markets while optimizing or exiting underperforming ones. Develop region-specific strategies that account for local market dynamics.

### Product Portfolio Management and SKU Rationalization

Focus resources on high-margin, high-volume products that drive disproportionate business value. Phase out low-performing SKUs to reduce supply chain complexity and inventory carrying costs. Introduce new products in categories showing strong consumer demand and market growth. Optimize product assortment by channel and region based on local preferences. Make informed decisions about brand positioning and repositioning opportunities.

### Revenue Growth and Profit Maximization

Optimize pricing strategies based on granular margin analysis and competitive positioning. Balance volume growth objectives with profitability goals to maximize shareholder value. Identify opportunities to reduce discounting while maintaining competitive market position. Improve revenue mix by shifting sales toward higher-margin products and channels. Capture additional revenue through cross-selling and bundle opportunities.

### Operational Efficiency and Supply Chain Optimization

Identify supply chain inefficiencies through analysis of regional sales patterns and inventory turnover. Optimize inventory levels based on demand forecasting to reduce working capital requirements. Reduce stockouts in high-demand regions that result in lost sales and customer dissatisfaction. Minimize excess inventory in slow-moving regions to free up cash and warehouse space. Improve production planning and procurement based on accurate demand predictions.

## Repository Structure and File Organization

```
FMCG-Analysis/
│
├── Images/
│   ├── FMCG-1.jpeg                 # Dashboard overview screenshot
│   ├── FMCG-2.jpeg                 # Product performance page
│   └── FMCG-3.jpeg                 # Regional analysis page
│
├── Power BI File/
│   └── FMCG_Analysis.pbix          # Complete Power BI dashboard file
│
└── README.md                        # Project documentation
```

## How to Use This Power BI Dashboard

**Step 1: Download Dashboard File**
Navigate to the Power BI File folder in this repository and download the FMCG_Analysis.pbix file to your local machine.

**Step 2: Install Power BI Desktop**
If not already installed, download the free Power BI Desktop application from the official Microsoft website. Power BI Desktop is required to open and interact with .pbix files.

**Step 3: Open Dashboard in Power BI**
Launch Power BI Desktop and open the downloaded FMCG_Analysis.pbix file using File > Open.

**Step 4: Refresh Data (Optional)**
If you have access to the original data source or an updated dataset, you can refresh the data by clicking Refresh in the Home ribbon. The dashboard will work with the embedded sample data without refresh.

**Step 5: Explore Interactive Features**
Use slicers and filters to explore different dimensions of the data. Click on visual elements to cross-filter other visuals. Drill down into hierarchies for detailed analysis.

**Step 6: Publish to Power BI Service (Optional)**
For sharing with stakeholders, publish the dashboard to Power BI Service using File > Publish. This requires a Power BI Pro or Premium Per User license for collaboration features.

## Technical Skills Demonstrated

This project showcases proficiency in the following data analytics and business intelligence competencies:

**Data Analysis** - Exploratory data analysis, statistical analysis, trend identification, and insight generation

**Data Visualization** - Creating effective visual representations of complex data for business audiences

**Business Intelligence** - Translating business requirements into analytical solutions and dashboards

**Data Modeling** - Designing efficient star schema data models with proper relationships and cardinality

**DAX Programming** - Writing calculated measures, columns, and time intelligence functions for advanced analytics

**ETL/Data Preparation** - Cleaning, transforming, and preparing data using Power Query M language

**Dashboard Design** - Creating user-friendly, intuitive dashboard layouts following UX best practices

**Business Acumen** - Understanding FMCG industry dynamics, KPIs, and strategic decision-making frameworks

## Related Resources and Learning Materials

**Dataset Source:** FMCG Multi-Country Sales Dataset on Kaggle
https://www.kaggle.com/datasets/robertocarlost/fmcg-multi-country-sales-dataset/code

**Power BI Documentation:** Official Microsoft Power BI Documentation
https://docs.microsoft.com/en-us/power-bi/

**DAX Reference Guide:** Comprehensive DAX Function Reference
https://dax.guide/

**Power BI Community:** Microsoft Power BI Community Forums
https://community.powerbi.com/

**Data Visualization Best Practices:** Storytelling with Data by Cole Nussbaumer Knaflic

## Project Author and Contact Information

**Nitin Girdhar**

**Current Role:** Project Trainer at Aharada Education (IIMT University)

**Career Goal:** Transitioning to Data Analyst role

**Technical Skills:** Python, SQL, Excel, Power BI

**Email:** [Your Email Address]

**LinkedIn:** [Your LinkedIn Profile URL]

**GitHub:** https://github.com/Nitin-data-domain

**Portfolio:** Explore more data analytics projects and visualizations in my GitHub repositories

## Keywords and Tags

Power BI Dashboard, FMCG Analysis, Sales Analytics, Business Intelligence, Data Visualization, DAX, Power Query, Multi-Country Sales, Revenue Analysis, Profit Analysis, Product Performance, Regional Performance, Promotional Analysis, KPI Dashboard, Interactive Dashboard, Data Analytics Project, Business Analytics, Sales Dashboard, Marketing Analytics, Retail Analytics, Consumer Goods Analysis, Data-Driven Decision Making, Portfolio Project

## Project License and Usage

This project is open-source and available for educational purposes, portfolio demonstration, and learning. Feel free to fork, modify, and use this dashboard as a template for your own analytics projects. Attribution to the original author is appreciated but not required.

## Acknowledgments and Credits

**Data Provider:** Kaggle contributor Roberto Carlos for publishing the FMCG Multi-Country Sales Dataset

**Platform:** Microsoft Power BI for providing powerful data visualization and analytics capabilities

**Inspiration:** Real-world business intelligence use cases in the FMCG and retail analytics domain

**Community:** Power BI community members for sharing knowledge, best practices, and DAX formulas

Built by Nitin Girdhar as part of a data analytics portfolio showcasing Power BI skills and business intelligence capabilities.
