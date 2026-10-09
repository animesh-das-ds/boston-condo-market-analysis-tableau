# Boston Condo Market Analysis — Interactive Tableau Story

![Course](https://img.shields.io/badge/Course-Data%20Visualization%20using%20Tableau-1f77b4)
![Grade](https://img.shields.io/badge/Grade-A%20(4.0)-success)
![Type](https://img.shields.io/badge/Type-Dashboard%20%C2%B7%20Story-blue)
![Tool](https://img.shields.io/badge/Tool-Tableau-orange)

**[▶ View the live interactive story on Tableau Public](https://public.tableau.com/app/profile/animesh.das6961/viz/Project_17704804684250/BostonCondoMarketAnalysisStory)**

An interactive Tableau story that analyses the Boston condominium market and translates the findings into a **design brief for a house-recommendation system**.

---

## Business Problem

Buyers in the Boston condo market face a wide, confusing range of options. A recommendation system needs to know which factors genuinely drive value and how to segment buyers, so it can suggest the right property to the right person.

## Objective

Build a multi-dashboard Tableau story that explores market size and distribution, property features, pricing dynamics, commercial (mixed-use) factors and market efficiency — then summarise the findings into strategic recommendations.

## Data

Boston-area condo sales records including sale price, area/zip code, interior square footage, bedrooms, bathrooms and rooms, property tax, price per square foot, and a commercial-establishment classification (**RC = 0** pure residential, **RC = 1** mixed-use).

## Story Structure

The workbook is built as a guided narrative:

| # | View | Purpose |
|---|---|---|
| 1 | Boston Area Zip Codes | Geographic starting point |
| 2 | Market Landscape | Market size and distribution |
| 3 | What Buyers Want | Property features that drive value |
| 4 | Pricing Dynamics | Pricing patterns and tax implications |
| 5 | Commercial Factor | Impact of mixed-use classification |
| 6 | Market Efficiency | Time on market and performance |
| 7 | Executive Summary | Key findings and recommendations |

Supporting sheets include `Distribution_of_SalePrices`, `Correlation_SqFt_SalePrice`, `PropertyTax_By_Neighbourhood`, `RC=1_Impact_SalePrices`, `Market_Trends_Over_Time`, `Sales_Volume_By_Area`, `Demand_Of_Condos_By_Area` and `Average_SalePrice_Area_KeyMetrics`.

## Key Findings

**Market landscape**
- Sale prices range from **$51,000 to $875,000** with a **median of $146,000**.
- Sales concentrate in areas **CP, M, and W**; the market spans entry-level to premium segments.

**Property characteristics**
- **Interior square footage correlates strongly with sale price** — it is the primary value driver.
- The most common configuration is **2 bedrooms / 2 bathrooms**; average rooms per property varies by price segment, indicating lifestyle-based buying.

**Pricing intelligence**
- Property tax burden varies enormously — **from $33 to $7,437** — which materially changes total cost of ownership.
- Price per square foot varies meaningfully by area, and some lower-priced properties actually carry **higher total ownership costs** once tax is included.

**Commercial impact**
- Properties allowing small commercial establishments (**RC = 1**) show distinct pricing patterns, concentrate in specific neighbourhoods, and appeal to an entrepreneurial buyer segment.

## Recommendations

1. **Multi-factor scoring for recommendations** — square footage 40%, area 25%, bed/bath configuration 20%, total cost 15%.
2. **Buyer segmentation framework** — an intake questionnaire classifying buyers into four segments: entry-level, mid-market, premium and mixed-use.
3. **Financial transparency** — show *Total First-Year Cost* (purchase + annual tax) and *5-year total cost of ownership* on every recommendation.
4. **Separate recommendation tracks** for pure residential (RC = 0) vs mixed-use opportunity (RC = 1) properties.
5. **Success metrics to track** — recommendation relevance > 4.0/5.0, viewing conversion > 25%, purchase conversion > 5%, time-to-match < 14 days, and 20% faster inventory turnover for recommended properties.

## Skills Demonstrated

Tableau dashboard and story design · geographic analysis · scatter and distribution analysis · calculated fields (price per square foot, total cost of ownership) · KPI definition · turning visual analysis into a product/strategy brief.

## Repository Structure

```
├── screenshots/
│   ├── 01_market_overview.png
│   ├── 02_property_characteristics.png
│   ├── 03_pricing_intelligence.png
│   ├── 04_commercial_impact.png
│   ├── 05_market_performance.png
│   └── 06_executive_summary.png
└── README.md
```

## Dashboard Previews

| Dashboard | Preview |
|---|---|
| 1 · Market Overview | `screenshots/01_market_overview.png` |
| 2 · Property Characteristics | `screenshots/02_property_characteristics.png` |
| 3 · Pricing Intelligence | `screenshots/03_pricing_intelligence.png` |
| 5 · Market Performance | `screenshots/05_market_performance.png` |

> The screenshots above are captures of the published Tableau Public story. For full interactivity, filters and tooltips, open the live story using the link at the top of this page.

---

*PGP in Data Science & Business Analytics · Great Lakes Executive Learning / The University of Texas at Austin, McCombs School of Business. Analysis built from the published Tableau story.*
