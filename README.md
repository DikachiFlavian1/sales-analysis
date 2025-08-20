## Sales Analysis

Plain-language documentation of a simple sales analysis with linked data files and an embedded image. No Python/Jupyter required.

### Data Files
- [SalesAnalysis..csv](./sales-Analysis/SalesAnalysis..csv)
- [SimpleSalesReport .xlsx](./sales-Analysis/SimpleSalesReport%20.xlsx)

### Visual
![Sales overview](./sales-Analysis/sales.png)

#### Key insights
- 📉 Net sales vs budget (Jun 1–10): 11.21M actual vs 18.88M budget (~59% to plan; ~7.67M shortfall).
- 🚶‍♂️ Traffic is the main gap: avg transactions 177/day vs budget 316/day (~56% of plan).
- 🧺 Basket strength: SPT averages ~6,958 vs budget ~6,037 (+15%). Basket value is solid; traffic is the constraint.
- 🔝 Best day: Fri 2025-06-06 with 1.65M net (228 transactions, SPT ~8,013). Weakest: Mon 2025-06-02 with 0.77M.
- 🌐 Online share is small: ~287k online net over the period (~2.6% of total). Biggest online lift on 2025-06-01 (~6% of day’s net).
- 📆 Seasonality: Weekends (Sun 6/1, Fri 6/6, Sat 6/7) outperform weekdays; plan promos and staffing accordingly.

#### Business recommendations
- 🎯 Traffic first: re-allocate spend to top-of-funnel and in-store footfall drivers. Target +30–40% transactions to close the gap; keep SPT tactics steady.
- 🧩 Targeted promos: avoid blanket discounts (SPT already strong). Use bundles and add-ons; run midweek boosters to smooth troughs.
- 🔀 Channel mix: grow online from ~2.6% toward 5–8% via paid search, retargeting, and click-and-collect; measure CAC to maintain margin.
- 🧭 Budget reset: revise transaction targets closer to observed run-rate; set stretch growth on traffic, not SPT.
- 🗂️ Ops planning: align inventory and staffing to peaks (Fri–Sun). Use daily forecasts to set reorder points and schedules.

#### KPIs to track
- 💰 Total net revenue, gross margin, AOV/SPT
- 🔁 Transactions, conversion rate (where measurable), repeat rate
- 🌐 Online share of sales, promo lift, return rate

Data quality note
- ⚠️ The CSV’s “TOTAL NET SALES” value for 2025-06-08 appears miscalculated (~22.8k vs ~1.20M expected = store net 1,180,828.83 + online 22,612.61). Please correct the source formula before reporting. 

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
sales-Analysis/            # repository root
  README.md                # this file (renders on GitHub)
  sales-Analysis/          # data and visuals folder
    README.md              # same documentation placed inside the folder
    SalesAnalysis..csv
    SimpleSalesReport .xlsx
    sales.png
```

---
**Author**: Kachi Flavian  
**Contact**: +2349021330176  
**Email**: chuksoflavian@gmail.com


