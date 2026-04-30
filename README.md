# Global Sales Performance Dashboard — Adventure Works

**Tools:** Microsoft Excel · Power Query · Data Modeling · Pivot Tables · Slicers  
**Dataset:** Adventure Works 2005–2008 · 60,000+ records · 6 markets  
**Full Analysis:** [View Slide Deck](https://docs.google.com/presentation/d/1vfT6LIx0B7X4Z2NCGZY-lDrr_0hzi1vJ/edit?slide=id.p2#slide=id.p2)

---

## Project Overview

Built an interactive Excel dashboard to analyze global sales performance across 6 markets 
(US, Australia, UK, Canada, Germany, France) over 4 years (2005–2008).

The goal was to go beyond surface-level metrics — identifying structural patterns in 
profitability, order behavior, and seasonality that differ by market.

---

## Technical Approach

- **ETL:** Used Power Query to extract, clean, and load 60,000+ transactional records 
  from raw source tables
- **Data Modeling:** Built a Star Schema connecting 5 tables — 
  `FactInternetSales`, `DimCustomer`, `DimProduct`, `DimGeography`, `DimDate`
- **Dashboard:** Designed dynamic visualizations with cross-filtering slicers, 
  KPI cards, and conditional formatting tracking Revenue, Profit Margin, AOV, 
  and transaction volume across markets and time periods

---

## Dashboard Preview

<img width="1212" height="724" alt="0cc6383b-355e-4696-86ac-c3835adfef7e" src="https://github.com/user-attachments/assets/11ed29ec-4fb8-4b5d-b5d4-013c7c3156cf" />


---

## Key Findings

| # | Finding | Implication |
|---|---------|-------------|
| 1 | US average order value ($4,573) is **56% lower** than Australia ($7,132) despite **60% more transactions** | US growth opportunity lies in upsell and product mix shift — not volume |
| 2 | **Q3 is the weakest quarter across all 6 markets** — US Q3 profit drops 44% vs Q2 | Structural gap, not random variance — addressable with a targeted campaign |
| 3 | Canada has the **highest profit margin (41.9%)** with the smallest revenue base | Cost model is scalable — pilot in UK and Germany to lift margins |
| 4 | Australia has the **lowest margin (40.6%)** despite being the 2nd largest market | Every 1% margin improvement = ~$952K additional profit without new customers |
| 5 | Europe (UK, DE, FR) all peak in **June and December** — Australia peaks **April–June** | No one-size-fits-all seasonal campaign — each market needs its own calendar |
