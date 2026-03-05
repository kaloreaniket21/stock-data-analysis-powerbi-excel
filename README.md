# 📈 NSE Stock Data Analysis Dashboard

[![Power BI](https://img.shields.io/badge/Tools-Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![Excel](https://img.shields.io/badge/Data%20Cleaning-MS%20Excel-217346?style=flat&logo=microsoftexcel&logoColor=white)](https://www.microsoft.com/excel)
[![NSE India](https://img.shields.io/badge/Source-NSE%20India-blue)](https://www.nseindia.com/)

An end-to-end data analytics project exploring 1 year of historical National Stock Exchange (NSE) data. This project demonstrates data modeling, ETL (Extract, Transform, Load) processes, and interactive visualization to uncover market trends and price volatility.

##  Project Overview
This project analyzes stock performance over a 12-month period to help investors visualize price movements and volume trends. By cleaning raw exchange data and building a robust data model, the dashboard provides a high-level view of 52-week highs/lows, daily opening/closing gaps, and monthly volume distribution.

### Key Questions Answered:
* What is the average 52-week price range for the selected period?
* Which months saw the highest trading volume and liquidity?
* How does the daily Open-Close delta fluctuate across different months and quarters?

---

##  Tech Stack & Workflow
* **Data Source:** Raw historical stock data (.csv) from the [NSE Website](https://www.nseindia.com/).
* **Data Cleaning:** **Microsoft Excel** used for initial formatting, handling missing values, and data type standardization.
* **Data Modeling:** **Power BI (Power Query)** used to create a star schema, define date tables, and establish relationships.
* **Visualization:** **Power BI Desktop** for building interactive charts, slicers, and KPI cards.

---

## Dashboard Highlights
The interactive dashboard includes several critical views for financial analysis:

1. **Price Performance KPIs:** High-level cards showing Average 52W High ($2.15K), Average 52W Low ($1.53K), and Total Volume ($349M).
2. **Temporal Trends:** * **Quarterly Analysis:** Stacked bar charts showing the 52W High vs. Low spread by Q1-Q4.
   * **Daily Volatility:** Line charts tracking the Sum of Open and Close prices by day of the month.
3. **Volume Distribution:** A horizontal bar chart identifying monthly trading peaks (e.g., March and June showing significant volume spikes).
4. **Interactive Slicers:** Dynamic filtering by Day, Month, Quarter, and Year for granular analysis.


---

##  Key Insights Derived
* **Seasonal Volume:** Trading volume peaked in **March** and **June**, indicating periods of high market activity or institutional rebalancing.
* **Stability Trends:** The gap between 52W High and Low remained relatively consistent across all four quarters, suggesting a period of steady market growth rather than extreme volatility.
* **Daily Patterns:** Price movements showed significant fluctuations around the mid-month period (Days 10-20), as seen in the multi-layered area charts.

---

## 🚀 How to Use This Project
1. **Download the `.pbix` file:** Download the Power BI file from this repository.
2. **Open in Power BI Desktop:** Ensure you have the latest version of Power BI Desktop installed.
3. **Explore Slicers:** Use the top navigation bar to filter data by specific months or quarters to see how the KPIs update in real-time.

---

##  Author
**Aniket Kalore** *Data Analyst*

📧 [kaloreaniket21@gmail.com](mailto:kaloreaniket21@gmail.com)  
🔗 [LinkedIn]( www.linkedin.com/in/aniket-kalore-9710712b0) 
     | [GitHub] https://github.com/kaloreaniket21
