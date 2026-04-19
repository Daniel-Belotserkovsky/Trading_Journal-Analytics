# Trading Journal & Analytics Engine
Trading Journal and Analytics Engine: T-SQL database architecture and Power BI dashboard for performance research and strategy attribution.

## Key Features

### 1. Relational Database Architecture (SQL)
Designed a **normalized T-SQL schema** to manage trading data with high integrity.
* **Core Tables:** `Stocks`, `StockPrices`, and `Trades`.
* **Data Integrity:** Implemented Primary/Foreign keys and **CHECK constraints** to ensure ledger accuracy across 3,000+ price records.

### 2. Quantitative Dashboard (Power BI)
Built an interactive suite to visualize performance metrics and equity growth.
* **Matched Trades:** Engineered logic to calculate profit/loss, win rates, and holding periods.
* **Strategy Research:** Isolated performance by technical signal, identifying the **150-day Moving Average** as a high-probability trigger.

---

## Files
* `Trading_Journal Final.sql`: Database creation and schema definition.
* `Trading_Journal.pbix`: Full Power BI report with interactive visuals.
