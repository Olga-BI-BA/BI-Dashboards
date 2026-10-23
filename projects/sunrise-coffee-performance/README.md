# Sunrise Coffee: 2023–24 Performance Review

A Power BI report for the Chief Commercial Officer. It reviews store profitability, the loyalty programme and the revenue mix across 60 UK stores, and ends with a costed plan for 2025.

## 1. Business question

**Role:** senior commercial analyst at Sunrise Coffee Chain, reporting to the Chief Commercial Officer.

**Scenario:** the commercial team suspects performance is diverging between formats and regions. The review covers the 2023–2024 trading period and feeds two decisions:

- **2025 site selection:** which regions and formats to prioritise.
- **The loyalty scheme:** whether it deserves further investment.

The four analysis areas from the brief:

1. **Store format and regional performance**, including which stores to review or close.
2. **Loyalty programme effectiveness**, including its net value against redemption cost.
3. **Revenue mix and product category trends** across espresso, filter, food and retail beans.
4. **Temporal and seasonal patterns** by weekday, bank holiday and season, to plan staffing and stock.

## 2. Key findings

1. **London is where profit leaks.** Its net margin is 8.5% against 18.8% for the estate. Rent takes 19% of its sales (10% estate-wide), and 29% of its store-months lost money.
2. **Staffing, not rent, drives margin.** Staffing tracks margin far more closely than rent (r = −0.83 vs −0.46). It takes 31.1% of sales.
3. **Staffing does not follow demand.** Weekends trade 24% below weekdays and bank holidays 34% below a standard day, in every location. Yet weekend staff hours match weekdays.
4. **Loyalty pays back only where people join.** Rewards return 2.6× where 40%+ of customers join, but only 0.3× below 20%. Members do not spend more per visit. Regional differences in adoption are not statistically significant (ANOVA p = 0.28).
5. **There is no fixed season.** High-street months stay within ±5% of an average month. The two years do not repeat (r = −0.49), and the peak quarter moved from Q3 2023 to Q1 2024. The calendar matters more than the month.
6. **Christmas splits by location.** Shopping centres gain 9% and city centres 3% over Christmas, but suburban stores lose 11%, in both years.
7. **The revenue mix is almost identical everywhere and stable.** Filter coffee earns the highest unit margin; retail beans trail.
8. **14 stores need action:** 1 potential closure, 7 to review and 6 to watch.

## 3. 2025 Plan: £1.76M a year, +21% on FY2024 net profit

| Action | Yearly impact |
|---|---|
| Roster weekends 25% lighter | £0.99M |
| Staff bank holidays a third lighter | £0.08M |
| Renegotiate rents above 12% of sales | £0.55M |
| Redesign rewards in the 17 low-adoption stores | £0.14M |
| Open the next stores outside London (Northern Ireland, West Midlands, Wales, East of England) | +£181k per new store (London: £54k) |
| Act on the 14 flagged stores | — |

Net margin rises from 18.8% to 22.7%, and staffing falls from 31.1% to 28.7% of sales, below the 31% cap.

## 4. Answers to the brief's guiding questions

**Store and format performance**

| Question | Answer | Page |
|---|---|---|
| Which format has the highest net margin? | Transport-Hub at 25.1% vs High-Street at 18.6%, but Transport-Hub is only 2 stores. The data has no Retail-Park stores. | Overview, Stores |
| Where do loss-making months concentrate? | London: 29% of its store-months lost money, against 14% for the estate. | Regions |
| Does higher rent bring higher revenue? | No. Revenue per store is flat across rent bands while margin falls as rent rises; London rent takes 19% of sales. | Regions, Cost Drivers |
| Most improved and most deteriorated stores, 2023 → 2024? | Improved: Belfast Yard (+£117k) and Liverpool Collective (+£116k). Deteriorated: Bristol Station (−£141k) and South London Corner (−£108k). | Stores, Store Table |

**Loyalty programme**

| Question | Answer | Page |
|---|---|---|
| Does adoption correlate with member revenue share? | Yes, almost perfectly (r = 0.998). | Loyalty |
| Do members spend more per transaction? | No. Adoption is unrelated to average transaction value (r = −0.06), at about £7.28 in every band. | Loyalty |
| What is the programme's net value? | Overall, £2.06M of extra revenue against £1.73M of rewards (1.19×). The return is 2.6× in high-adoption stores but 0.3× below 20% adoption. | Loyalty, 2025 Plan |
| Does adoption vary by format or region? | It ranges from 17% to 45% by region, but the differences are not significant (ANOVA p = 0.28). | Loyalty |

**Revenue mix**

| Question | Answer | Page |
|---|---|---|
| How is daily revenue split? | Espresso 45.7%, food 26.1%, filter 19.2%, retail beans 9.0%. The split is almost the same in every format and location. | Menu Mix |
| Which categories carry the highest gross margin? | Filter coffee (88%) and espresso (84%); retail beans are lowest (68%). Filter's share is not growing. | Menu Mix |
| Is food growing? | No: 26.2% in 2023, 25.9% in 2024. | Menu Mix |
| Are retail beans growing? | Slightly: 8.9% → 9.2%. | Menu Mix, Store Detail |

**Seasonal and temporal patterns**

| Question | Answer | Page |
|---|---|---|
| Weekday vs weekend by format? | Weekends are 24% below weekdays for High-Street and 27% below for Transport-Hub. | Seasonality |
| Do bank holidays help or hurt Transport-Hub vs High-Street? | They hurt both about equally: −34% vs a standard day. | Seasonality |
| Best and worst months; does the pattern repeat? | Best: Nov 2024 (£817k). Worst: Nov 2023 (£564k). The two years do not repeat (r = −0.49). | Seasonality |
| Peak trading quarters? | Q3 in 2023 and Q1 in 2024 (£2.27M). The peak moves from year to year. | Seasonality |
| How do formats respond to seasonal shifts? | High-Street months stay within ±5% of an average month. Transport-Hub swings more (summer +9%, January −14%), but it is only 2 stores. | Seasonality |

**Brief deliverables → report**

| Deliverable | Where |
|---|---|
| Executive summary and headline recommendation | Overview and 2025 Plan |
| Profitability trends, format comparisons, revenue mix | Overview, Regions, Menu Mix, Seasonality |
| Store-level breakdown with profitability status | Stores, Store Table, Store Detail |
| Loyalty net value assessment | Loyalty |
| Stores and regions for review, loyalty investment call, seasonal staffing | 2025 Plan, Store Table, Seasonality |

## 5. Report walkthrough

| Page | What it answers |
|---|---|
| **Overview** | Estate headline KPIs, the profit trend and four headline recommendations |
| **Regions** | Where margin leaks and which regions to grow in; rent bands vs margin |
| **Cost Drivers** (hidden, opened from Regions) | Staffing vs rent as margin drivers |
| **Stores** | Store ranking and the watch list of flagged stores |
| **Menu Mix** | Category shares and margins, by store and over time |
| **Loyalty** | Adoption, spend per visit and payback by adoption band |
| **Seasonality** | Weekdays, weekends, bank holidays and months, by format and location |
| **2025 Plan** | The costed action plan, with a savings waterfall |
| **Store Table** | Every store, with its recommended action |
| **Store Detail** (hidden; opened by drill-through from any store) | One store's passport, rankings and why it is flagged, with Profitability / Loyalty / Revenue mix tabs |
| **How to use** (hidden; opened from the ? button in the sidebar) | A guide to the controls, plus data notes |

## 6. Interactivity

- Cross-filtering on every page and a Reset button.
- Drill-through from any store (right-click, Drill through) to the hidden Store Detail page.
- Bookmark tabs on Store Detail and Loyalty, and a "Show by months" heat-map toggle on Seasonality.
- Field-parameter switches: Month / Quarter, Format / Location and Staffing / Rent.
- Report-page tooltips for stores, and header "?" tooltips that explain the method, ANOVA and data gaps.
- Dynamic titles that state the finding for the current selection, for example "Northern Ireland is a profit engine" or "London is where profit leaks".
- A Location slicer that drives the day and holiday visuals only.

## 7. Data model and DAX

- **Source data (GBP):** `dim_store` (60 rows), `dim_product` (40), `dim_date` (730), plus two facts:
  - `fact_store_monthly_profitability`: 1,440 rows, 60 stores × 24 months; full P&L, loyalty and footfall. Used for profitability and trends.
  - `fact_daily_sales`: 10,000 rows, store × day × top product. Used for day-of-week and mix patterns.
- **Star schema:** both facts link to store, month or date, and product dimensions.
- **Field parameters:** Period, Seasonal Group and Cost Driver. **Small helper tables:** `SD Metric`, `Plan Lever` and `Plan Action`.
- **Notable DAX:**
  - seasonal index (revenue per store-month ÷ average month, using `ALLSELECTED`);
  - Pearson correlation written in DAX;
  - peer rankings with `RANKX` over same-location stores;
  - peer and estate benchmarks;
  - conditional colour measures for ranks and gaps;
  - plan savings and the waterfall built from data, not typed in.
- Helper and formatting measures are hidden and grouped into display folders.

## 8. Data limitations

- The monthly P&L is complete (60 stores × 24 months). Every £ figure uses it.
- Daily sales are a 10,000-row sample, so day and holiday effects are shown as % vs a standard day.
- 68 duplicate store-date-product rows and 140 rows with staff above headcount are flagged.
- The source profitability status disagrees with the P&L in 600 of 1,440 store-months, so the report recalculates it.
- There are no Retail-Park stores in the data, only High-Street and Transport-Hub. Transport-Hub has just 2 stores, so treat its results as indicative.
- The calendar ends on 30 Dec 2024.

## 9. Assumptions behind the plan

- Staff hours flex with demand, and lighter rotas do not cut sales.
- Landlords accept rent at 12% of sales, or the store relocates.
- Extra member revenue is estimated from the member spend premium.
- Savings are yearly upper bounds on an FY2024 basis. New stores add on top.

## 10. Tools and design

- Power BI Desktop.
- Colour scheme: Navy `#12354E`, Raw Sienna `#BB7125`, Cinnamon `#EEA78C`, Ecru `#C2AE93`.
- Segoe UI throughout, on a 1280×720 canvas with custom SVG page backgrounds.
