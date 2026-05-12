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

<img width="1510" height="514" alt="Screenshot 2026-05-12 165432" src="https://github.com/user-attachments/assets/d272afdd-28f4-45b4-a18f-7fe293258a3b" /><img width="1118" height="700" alt="Screenshot 2026-05-12 165149" src="https://github.com/user-attachments/assets/fc0b89a9-9591-41e3-91d1-77219b4a35fc" />




---

## Key Findings

| # | Finding | Implication |
|---|---------|-------------|
| 1 | US average order value ($4,573) is **56% lower** than Australia ($7,132) despite **60% more transactions** | US growth opportunity lies in upsell and product mix shift — not volume |
| 2 | **Q3 is the weakest quarter across all 6 markets** — US Q3 profit drops 44% vs Q2 | Structural gap, not random variance — addressable with a targeted campaign |
| 3 | Canada has the **highest profit margin (41.9%)** with the smallest revenue base | Cost model is scalable — pilot in UK and Germany to lift margins |
| 4 | Australia has the **lowest margin (40.6%)** despite being the 2nd largest market | Every 1% margin improvement = ~$952K additional profit without new customers |
| 5 | Europe (UK, DE, FR) all peak in **June and December** — Australia peaks **April–June** | No one-size-fits-all seasonal campaign — each market needs its own calendar |
