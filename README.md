# Shopify Stock Performance & Market Analysis Dashboard

## 📊 Project Overview
This Power BI project analyzes historical Shopify stock data using Open, High, Low, Close, Adjusted Close, and Volume values. The dashboard provides interactive insights into stock price trends, trading volume, monthly performance, and YTD performance.

## 🎯 Objectives
- Analyze Shopify stock price trends.
- Track Open, High, Low, and Close prices.
- Analyze trading volume.
- Monitor monthly and yearly performance.
- Calculate average and latest closing prices.
- Analyze YTD performance.
- Compare current and previous-period closing prices.
- Provide interactive date-based filtering.

## 🗂️ Dataset
The main table is `shopify_stock`.

Columns:
- `date` – Stock trading date
- `open` – Opening price
- `high` – Highest price
- `low` – Lowest price
- `close` – Closing price
- `adj_close` – Adjusted closing price
- `volume` – Trading volume

The Date table contains Date, Day, Month, Month_name, Quarter_year, Week, and Year.

## 📈 Dashboard Features
- Latest Closing Price
- Average Closing Price
- YTD Closing Price
- Total Trading Volume
- Highest Price
- Lowest Price
- Price Change
- Price Change %
- Closing Price Trend
- Average Closing Price by Month
- Daily Open/High/Low/Close Analysis
- Daily Trading Volume
- YTD Performance

## 🧮 DAX Measures
`Total Volume = SUM(shopify_stock[volume])`

`Highest Price = MAX(shopify_stock[high])`

`Lowest Price = MIN(shopify_stock[low])`

`Price Change = [Latest Close] - [Close_P_Month]`

`Price Change % = DIVIDE([Latest Close] - [Close_P_Month], [Close_P_Month], 0)`

## 🎛️ Filters
The dashboard includes Year, Month, Quarter, and Date Range slicers for interactive analysis.

## 🛠️ Tools & Technologies
- Microsoft Power BI
- Power Query
- DAX
- Data Modeling
- Data Visualization

## 📌 Key Insights
The dashboard helps identify stock price trends, monthly variations, high and low prices, trading activity, and year-to-date performance.

## 🚀 How to Use
Open `powerBi_T3.pbix` in Power BI Desktop, use the available slicers to select a time period, and interact with the KPI cards and visualizations to analyze Shopify stock performance.

## 📁 Project Files
- `powerBi_T3.pbix`
- `README.md`

## 📌 Conclusion
The Shopify Stock Performance & Market Analysis Dashboard provides an interactive and visual approach to analyzing historical stock market data using Power BI, DAX, and data visualization techniques.
