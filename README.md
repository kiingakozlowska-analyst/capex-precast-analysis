# capex-precast-analysis
Bottom-up CAPEX model and sourcing analysis for precast concrete structural package

# CAPEX & Sourcing Analysis – Precast Concrete Structural Package

**Author:** Kinga Kozłowska  
**Date:** April 2026  
**Tools:** Excel (parametric model) · Tableau Public (interactive dashboard)  
**Domain:** Capital project analysis · Construction economics · Sustainability

---

## Business Question

Where should a precast concrete structural package be sourced — Norway, Poland or Germany — to minimise total project CAPEX? And under what conditions does that answer change?

---

## Project Overview

A bottom-up parametric CAPEX model for a precast concrete structural package referencing a multi-use civic development of 25,000 m² GFA. The scope covers five element types: hollow core slabs, sandwich wall panels, columns, beams and retaining walls.

All assumptions are documented with public sources and professional judgement from direct project experience at Spenncon AS (2019–2024). The model is fully parametric — every input is a yellow cell that drives downstream calculations.

---

## Methodology

**Cost decomposition — three layers:**
- **Production** — factory-gate cost per element type, adjusted for location (labour cost differential Norway / Poland / Germany)
- **Transport** — weight-based truck count, split by cargo type: flat transport (HC slabs, columns, beams) and vertical A-frame transport (sandwich walls, retaining walls), multiplied by market rate per truck per location
- **Erection** — crane cost (fixed, always on Stavanger site) + crew cost (varies by posted worker origin)

**Three production location scenarios:** Norway · Poland · Germany

**Additional analyses:**
- Break-even transport rate: at what Poland freight rate does offshoring become cost-competitive?
- Sensitivity analysis: which cost variables drive the most CAPEX risk?
- Carbon premium analysis: what is the financial cost of specifying Low-Carbon Class A concrete vs standard C35/45?

---

## Key Findings

1. **Norway local sourcing is the lowest-cost option** at 28.8M NOK (166 €/m²). Production, transport and erection all favour proximity.

2. **Poland's 58% production cost advantage is fully neutralised by transport.** Logistics from Poland (23.6M NOK) cost 3× more than local Norwegian sourcing (7.9M NOK) — making Poland 16.3% more expensive overall.

3. **Poland becomes viable only through logistics optimisation.** Break-even transport rate: 33,644 NOK/truck — a 20% reduction from the current market rate, achievable through volume freight contracts on larger project scopes.

4. **Germany offers no strategic advantage** — mid-range on every cost dimension, 10.8% more expensive than Norway.

5. **HC Slab price and transport cost drive 90% of CAPEX sensitivity.** A ±20% change in either moves total CAPEX by ±5.3%. Structural frame elements carry limited risk.

6. **Low-Carbon Class A concrete (confirmed on Lervigskvartalet, Spenncon AS) saves 271 tonnes of embodied CO₂** at a net cost of 905,171 NOK after EU ETS carbon value. Financial break-even requires ETS to reach 353 €/t — a 443% increase from today's ~65 €/t, consistent with long-term EU carbon pricing trajectory.

---

## Files

| File | Description |
|------|-------------|
| `CAPEX_Analysis_Final.xlsx` | Full parametric bottom-up CAPEX model — 5 sheets: Assumptions (with sources), Bill of Quantities, CAPEX Model, Carbon Analysis, Sensitivity Analysis |
| `Tableau_Clean_FINAL.xlsx` | Clean long-format data export for Tableau — 4 sheets: CAPEX Breakdown, Scenario Summary, Carbon Analysis, Sensitivity |
| `Breakeven_Analysis_CAPEX.xlsx` | Break-even analysis — Poland transport rate vs Norway fixed CAPEX across full rate range |

---

## Interactive Dashboard

**[View on Tableau Public →](https://public.tableau.com/app/profile/kinga.kozlowska/viz/CAPEXSourcingAnalysis/CAPEXSourcingComparison)**

Dashboard covers two pages:
- **Page 1:** CAPEX sourcing comparison (Norway / Poland / Germany) + break-even analysis
- **Page 2:** Cost risk (sensitivity tornado) + sustainability (carbon premium analysis)

---

## Data Sources

| Source | Used for |
|--------|----------|
| Skanska press release (2022) + Stavanger Kommune | Project GFA and total budget — Lervigskvartalet |
| Spenncon AS project reference | Precast scope 25,000 m², Low-Carbon Class A <220 kg CO₂/m³ confirmed |
| Elematic / Block Berge Bygg case study | HC slab unit price benchmark (330M NOK / ~400,000 m²) |
| FIB Bulletin 43 | Sandwich wall price ratio, erection productivity rates |
| SSB Statistics Norway (table 07685) | Norwegian manufacturing labour cost per FTE |
| GUS Poland / Destatis Germany | Polish and German wage benchmarks for location cost factors |
| Arcadis International Construction Costs 2024 | International transport rates, location cost factors |
| European Environment Agency (EEA) | EU ETS average price 2024: €65/t CO₂ |
| Norges Bank | EUR/NOK exchange rate April 2026: 11.60 |
| EN 15804 / EPD-Norway | Standard concrete CO₂ intensity: ~310 kg CO₂/m³ |
| Professional judgement — Kinga Kozłowska (Spenncon AS 2019–2024) | Project scope split, erection rates, element weight assumptions |

---

## About

This project was built to demonstrate capital project analysis thinking — bottom-up cost modelling, location sensitivity, logistics optimisation and sustainability cost quantification — directly applicable to roles in capital project advisory and should-cost analysis.

Background: MSc Structural Engineering (University of Stavanger) · 4.5 years designing precast concrete structures for large-scale infrastructure projects in Norway (Lervigskvartalet, SUS Hospital, Alta Handelspark) · MBA Essentials, LSE.
