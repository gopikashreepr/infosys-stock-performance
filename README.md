# Infosys Stock Performance Dashboard
**Tools:** Power BI · DAX · Time Series Analysis  
**Domain:** Financial Analytics · Stock Market  

---

## Business Problem
An investment analyst needs a clear, visual overview of Infosys stock performance over time — covering price trends, trading volume, and moving averages — to support buy/sell/hold decisions and identify periods of volatility or momentum.

## Dataset
- Source: Infosys (INFY) historical stock data
- Key fields: Date, Open, High, Low, Close Price, Volume, 20-Day Moving Average
- Time range: Multi-year historical data

## Dashboard Overview
Single-page comprehensive stock performance dashboard with 6 KPI cards and 4 analytical charts:

| Visual | Insight |
|---|---|
| Line chart | **Close Price + 20-Day Moving Average** — trend and momentum signal |
| Line chart | **Close Price by Year** — annual price trajectory |
| Area chart | **Trading Volume by Year** — market activity over time |
| Donut chart | **Volume Distribution by Year** — proportional activity breakdown |
| Bar chart | Year-over-year performance comparison |
| 6 KPI cards | Current price, avg close, high, low, avg volume, and price change % |

**Slicers:** Filter by year, quarter, and time period for focused analysis

## Key Business Questions Answered
1. What is the overall price trend for Infosys stock over the analysis period?
2. How does the 20-day moving average signal momentum and potential reversal points?
3. Which years had the highest trading volume — and what does that indicate about investor activity?
4. What are the all-time high and low price points, and when did they occur?

## Key Insights
- Moving average overlay reveals when the stock was in an uptrend (price above MA) vs correction phase (price below MA)
- Volume analysis identifies periods of high investor interest that often precede significant price movements
- Year-over-year comparison enables long-term performance benchmarking against market cycles

## Tools & Techniques
- Power BI Desktop — single-page dashboard with financial visuals
- DAX — moving average calculation, price change %, YoY metrics
- Time intelligence — year and quarter slicing
- Area charts — cumulative volume visualisation

## How to Run
1. Download `Infosys_Stock_Performance_Dashboard.pbix`
2. Open in Power BI Desktop
3. Use year and quarter slicers to zoom into specific time periods

---
*Project by Gopikashree PR | [LinkedIn](https://www.linkedin.com/in/gopikashree-pr/) | [GitHub](https://github.com/gopikashreepr)*
