# Hi there 👋

I'm a **Data Analyst** with 3+ years of experience in BI and research across corporate and non-profit environments, specializing in analytics pipelines, automation, and data engineering.

---

## Projects

## 🔷 Data Pipelines & Warehouses

#### [Medallion Pipeline — DB1B Airline Origin and Destination Survey](https://github.com/Elvi3n/Fabric-Medallion-Pipeline-Airline-Origin-and-Destination-Survey-DB1B)
`Microsoft Fabric` `PySpark` · *April 2026*

An end-to-end automated data pipeline processing airline ticket samples (DB1B) using a modular Medallion Architecture (Bronze → Silver → Gold) to assess airline performance.

- Developed notebooks with dynamic batch processing using shared timestamps, ensuring data lineage and isolated processing of the latest data increments
- Architected an event-driven orchestration flow using Azure Event Grid and Fabric Reflex to enable zero-intervention ingestion upon file arrival in ADLS Gen2
- Standardized raw datasets into analytics-ready gold tables through schema enforcement, type-casting, and aggregations to drive airline traffic pattern insights

---

#### [BI Analytics Pipeline — NYC Yellow Taxi](https://github.com/Elvi3n/Fabric-BI-Analytics-Pipeline-NYC-Yellow-Taxi)
`Microsoft Fabric` `SQL` `Power BI` · *March 2026*

A full data lifecycle solution in Microsoft Fabric, migrating data from a Lakehouse to a SQL Data Warehouse to power executive Power BI reports.

- Engineered a metadata-driven staging pipeline using T-SQL and dynamic expressions to automatically identify, fetch, and process the next available monthly data batch
- Implemented data quality controls via stored procedures to enforce schema standards, perform denormalization joins, and purge temporal outliers
- Developed a governance framework with a centralized metadata audit log capturing pipeline run IDs, row counts, and processing latency across all layers

---

#### [BI Analytics Pipeline — Restaurant Inspection Analytics](https://github.com/Elvi3n/Fabric-Power-BI-Service-Restaurant-Inspection-Analytics)
`Microsoft Fabric` `Power BI Service` · *February 2026*

An automated BI pipeline on Microsoft Fabric ingesting source files via an on-premises data gateway into a Dataflow Gen2 layer through scheduled pipeline refresh into a semantic model.

- Developed a star schema data model in Power BI Desktop and authored DAX measures calculating KPIs including inspection scores and time-based trends
- Published the semantic model to Power BI Service as a centralized data source, enabling downstream report consumption with automated data refresh

---

#### [Medallion Pipeline — Sales Data ETL](https://github.com/Elvi3n/SQL-Sales-ETL-and-Analytics-Pipeline)
`SQL` · *May 2025*

Warehoused raw CRM and ERP CSV exports into a structured SQL environment using Medallion Architecture (Bronze → Silver → Gold) for analytics and reporting.

- Modeled 60,000+ sales records and 18,000+ customer records into a Star Schema with fact and dimension tables, resolving conflicting CRM/ERP attributes into unified analytical entities
- Implemented reusable SQL validation and transformation rules to ensure high-quality data in the gold layer

---

## 🔶 Business Intelligence

#### [BI Analysis — Product Performance & Customer Behavior](https://github.com/Elvi3n/Power-BI-Sales-Product-Performance-Dashboard)
`Power BI` `DAX` · *May 2025*

Transformed three years of raw transactional data into a multi-page interactive dashboard using Power Query for ETL and a Snowflake schema relational data model.

- Built a DAX library calculating rolling averages, target gap analysis, and percentage-of-total contributions to monitor regional and category-level performance
- Implemented What-If price modeling to simulate the impact of price adjustments on total profitability
- Designed dynamic drill-through views for product and customer segments, surfacing high-return items and key purchasing patterns

---

#### [BI Analysis — Sales & Customer Segmentation](https://github.com/Elvi3n/SQL-BI-Sales-and-Customer-Segmentation-Analysis)
`SQL` · June 2025

SQL transformations to analyze time-based trends, seasonality, and year-over-year growth using window functions and aggregated gold layer tables.

- Generated key business KPIs including monthly sales performance, cumulative annual totals, and revenue contribution by customer and product segment
- Built customer and product segmentation models to evaluate profitability and identify targeted selling opportunities

---

#### [BI Demand Forecasting — Multi-Model Approach](https://github.com/Elvi3n/BI-Inventory-Demand-Forecasting-Analysis-Multi-Models)
`Excel` `DA Toolkit` `Solver` · December 2025

A forecasting framework classifying products into stable, seasonal, trend-based, and hybrid demand patterns using statistical models to improve forecast accuracy.

- Applied mean, seasonality indices, linear regression, and hybrid models to match forecast method to demand pattern type
- Validated demand trends using R² and translated outputs into procurement-aligned projections to mitigate overstock and stockout risks

---

#### [BI Analysis — Product & Margin Efficiency](https://github.com/Elvi3n/Product-Performance-Margin-Efficiency-BI-Analysis/tree/main)
`Excel` `Power Query` `Power Pivot` `DAX` · December 2025

An Excel BI model integrating 269,000+ retail transaction records with product, customer, regional, and calendar dimensions into a star schema for product-level profitability analysis.

- Developed reusable DAX measures for revenue, profit, rolling metrics, cumulative contributions, and rank-based performance indicators
- Designed profit vs. revenue rank comparisons to identify margin efficiency gaps and surface high-margin, under-the-radar performers

---

#### [BI Analysis — Retail Sales & Customer Behavior](https://github.com/Elvi3n/Retail-Sales-Customer-Insights-Dashboard)
`Tableau` · Novemeber 2025

Interactive Tableau dashboards analyzing 9,900+ order records across sales, profit, and quantity KPIs with year-over-year comparisons and dynamic monthly/weekly trend views.

- Built product and customer performance views including subcategory comparisons, profit/loss analysis, and top-customer ranking

---

## 🔹 Research

#### [Sentiment Analysis - Mastercard Sponsorship Reception Among League of Legends Players](https://github.com/Elvi3n/Mastercard-Brand-Analysis-in-r-leagueoflegends)
`Python` `Tableau` · October 2025    

Brand reception analysis of Mastercard the subreddit r/leagueoflegends using PRAW, Python Reddit API Wrapper. 

•	Developed an interactive Tableau dashboard to visualize sentiment trends, visibility peaks during the World Championship, and topic modeling for stakeholders.
•	Automated community feedback collection via Reddit API (PRAW), scraping and analyzing sentiment intensity from high-volume discussions in the r/leagueoflegends community.
•	Identified key drivers of brand perception, revealing that while production value drives positive sentiment, ticketing and botting issues are the primary sources of friction for cardholders.

#### [**Non-Profit Involvement**: GLOCAL Foundation of Canada — Canada Youth Unemployment Analysis](https://github.com/Elvi3n/GLOCAL-Canada-Youth-Unemployment)
`Python` · *June 2025*

A longitudinal labour-market analysis using ~50 years of Statistics Canada data (1978–2025) to quantify youth unemployment trends, duration, and gaps versus adult unemployment.

- Performed time-series and correlation analysis using pandas, NumPy, and matplotlib to identify rising long-term youth unemployment and widening entry-level job frictions
- Designed reproducible data pipelines and visualizations by cleaning and integrating multiple official Statistics Canada datasets
