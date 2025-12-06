📊 Indian Coal Stock Monitoring & Plant Performance Analysis (FY 2024–25)

A full Power BI analytics project designed to monitor India’s coal availability, transportation efficiency, and thermal power plant performance using real-time data.

📘 1. Project Overview & Objective

This project focuses on analysing India’s coal stock, indigenous/imported coal availability, supply chain efficiency, capacity distribution, and plant performance for FY 2024–25.
An interactive Power BI Dashboard was developed to support government planners, energy analysts, and utilities in data-driven decision-making.

🎯 Main Objectives

Provide real-time insights on coal availability across India.

Compare requirement vs receipt and identify coal shortages.

Analyse logistics performance (Rail, Road, Sea, Pithead, Others).

Study critical vs subcritical power plant performance.

Track state-wise & sector-wise generation capacity.

Support strategic energy planning with visual insights.

🔗 2. Data Sources
Source	Description
India Data Portal	Coal Stock & Plant Load Factor dataset
URL	https://indiadataportal.com/p/power/r/mop-coal_stock-pl-dl-aaa

Timeline	2018 – 2025
Domain	Energy, Power Generation, Industrial Analytics
❗ 3. Problem Statement

India’s thermal power sector heavily depends on coal. To ensure uninterrupted power generation, it is essential to track:

Coal requirement vs receipt

Shortages across months/quarters

Imported vs indigenous coal contributions

Logistics & transportation modes

Plant Load Factor (PLF) efficiency

Sector-wise & state-wise capacity distribution

This dashboard answers these questions with actionable visual analytics.

🧾 4. Attribute (Feature) Details
Attribute	Data Type	Description
Date	Date	Daily coal stock record
Requirement	Numeric	Coal needed by plants
Consumption	Numeric	Coal consumed
Receipt	Numeric	Coal received
Shortage	Numeric	Requirement – Receipt
Sector	Categorical	Central, State, Private, JV
State	Categorical	Indian states & UTs
Imported Stock	Numeric	Monthly imported coal
Indigenous Stock	Numeric	Quarterly domestic coal
Transportation Mode	Categorical	Rail/Road/Sea/Pithead/Others
PLF	Numeric (%)	Plant Load Factor
Plant Type	Categorical	Critical / Subcritical
🛠️ 5. Tools & Technologies Used
Excel

Data cleaning

Normalization, format alignment

Imputation for thermodynamic conditions

Power BI

Data modelling (Star Schema)

DAX calculations

Interactive dashboards

Drilldowns, slicers, bookmarks

🔧 6. Data Pre-processing & Modelling
🧹 Data Cleaning Tasks

Removed duplicates, missing values

Standardized date formats

Cleaned plant-level irrelevant fields

Segmented Critical vs Subcritical plants

Prepared fact-dimension structure

🗄️ Data Model (Star Schema)

Fact Table: Indian Coal Stock

Dimensions:

Calendar

Power Stations

Sectors

Stations by State

📐 7. DAX Measures Created

Key measures include:

Total Requirement

Total Receipt

Coal Shortage

Average Stock Days

Imported %

Total Capacity (State/Sector)

Average PLF %

Indigenous Stock

Monthly Imported Stock

📊 8. Dashboard Pages & Visualizations
📍 Page 1: Coal Stock Monitoring
⭐ Key KPIs

🚩 Total Requirement: 980.45K Tonnes

📦 Receipt: 814.12K Tonnes

⚠️ Shortage: 166.34K Tonnes

📆 Avg. Stock Days: 22.56

🌍 Imported %: 0.10%

🧮 Normative Gap: 6.39M

📌 Visuals Used

Quarterly Requirement vs Consumption vs Receipt

Monthly Imported Stock Trend

Sector-wise Capacity (Donut Chart)

Average Stock Days by Sector

State-wise Total Capacity (Bar Chart)

Slicers (State, Date Range)

📍 Page 2: Supply & Plant Performance
⭐ Key KPIs

🚆 Rail: 489.98K

🚚 Road: 41.52K

🚢 Sea: 44.92K

⛏️ Pithead: 188.02K

📦 Total Stock: 14.96M

📌 Visuals Used

Indigenous Stock by Quarter

Critical vs Subcritical Plants (Donut Chart – 21 vs 169)

Average PLF Gauge (%)

Monthly PLF by Plant Type

Plant Performance Map of India

💡 9. Insights & Recommendations
📌 Descriptive Insights

Coal requirement is consistently higher than receipts → shortages persist.

Indigenous stock decreasing quarter-over-quarter.

Rail is the dominant transport mode.

89% of India's plants are subcritical.

📌 Diagnostic Insights

Shortages mainly due to low indigenous output & reduced imports post-December.

Central sector plants show lowest stock days → higher outage risk.

📌 Predictive Insights

Shortages likely to worsen in FY 2025–26 if indigenous supply keeps falling.

States with high capacity but low PLF (UP, Maharashtra) may face pressure.

📌 Prescriptive Insights

Increase coal imports during high-demand seasons.

Strengthen domestic coal logistics (especially for pithead stations).

Accelerate modernization to shift away from subcritical tech.

Improve stock days for central plants to maintain grid stability.

🏁 10. Conclusion

This project delivers an end-to-end Power BI solution for monitoring India’s coal ecosystem.
It helps:

Identify shortages

Track indigenous vs imported coal trends

Analyze PLF performance

Support efficient planning for the power sector

It demonstrates strong skills in Excel, Power Query, DAX, Data Modelling, and Interactive Power BI Reporting.
