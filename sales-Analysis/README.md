## Sales Analysis

Plain-language documentation of a simple sales analysis with linked data files and an embedded image. No Python/Jupyter required.

### Data Files
- [SalesAnalysis..csv](SalesAnalysis..csv)
- [SimpleSalesReport .xlsx](SimpleSalesReport%20.xlsx)

### Visual
![Sales overview](./sales.png)

#### Key insights
- 📉 Net sales vs budget (Jun 1–10): ~11.21M actual vs ~18.88M budget (~59% to plan; ~7.67M shortfall).
- 🚶‍♂️ Traffic gap: avg transactions 177/day vs budget 316/day (~56% of plan).
- 🧺 Basket strength: SPT averages ~6,958 vs budget ~6,037 (+15%). Basket value is healthy; traffic is the constraint.
- 🔝 Best day: Fri 2025-06-06 with ~1.65M net (228 transactions, SPT ~8,013). Weakest: Mon 2025-06-02 with ~0.77M.
- 🌐 Online share is small: ~287k online net over the period (~2.6% of total). Biggest online lift on 2025-06-01 (~6% of day’s net).
- 📆 Seasonality: Weekends (Sun 6/1, Fri 6/6, Sat 6/7) outperform weekdays; plan promos and staffing accordingly.

#### Business recommendations
- 🎯 Drive transactions: shift budget to footfall and awareness. Target +30–40% transactions; preserve SPT tactics that work.
- 🧩 Smart promos: avoid blanket discounts. Use bundles/add-ons; schedule midweek boosters to lift trough days.
- 🔀 Channel growth: expand online from ~2.6% to 5–8% via paid search, retargeting, and click-and-collect; monitor CAC vs margin.
- 🧭 Re-forecast: reset transaction budgets closer to current run-rate; set stretch on traffic, not ticket size.
- 🗂️ Operations: align inventory and staffing to peaks (Fri–Sun) and use daily forecasts for ordering and scheduling.

#### KPIs to track
- 💰 Total net revenue, gross margin, AOV/SPT
- 🔁 Transactions, conversion rate, repeat rate
- 🌐 Online share of sales, promo lift, return rate

Data quality note
- ⚠️ The CSV’s “TOTAL NET SALES” for 2025-06-08 is likely miscalculated (~22.8k vs ~1.20M expected = store net 1,180,828.83 + online 22,612.61). Please correct the formula upstream before reporting.

---
**Author**: Kachi Flavian  
**Contact**: +2349021330176  
**Email**: chuksoflavian@gmail.com

### What this includes
- A CSV and an Excel workbook containing the raw/cleaned sales data
- A single image summarizing the key visual from the analysis
- This README for context and navigation

### How to use
- Click the links above to preview/download the data on GitHub
- The image renders directly on GitHub; open it full-size for details
- Open the Excel file to explore pivots/tables or build your own charts

### Repository structure
```text
sales-Analysis/
  README.md
  SalesAnalysis..csv
  SimpleSalesReport .xlsx
  sales.png
```


