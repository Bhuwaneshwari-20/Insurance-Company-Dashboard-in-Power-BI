# EIC Insurance Analytics — A Company's Rise and Collapse

## About the Project

EIC was a well-known name in the motor insurance space between 2014 and 2018, building a large and diverse customer base across vehicle types. Yet behind the growth, the numbers told a different story — claims consistently outpaced premiums, eroding the business year after year until EIC shut its doors in 2019.

This project uses Power BI to dig into EIC's five years of policy and claims data, tracing exactly where the business bled money, which segments were quietly profitable, and how close (or far) the company ever got to breaking even.

## What This Analysis Set Out to Answer

- Did the premiums EIC collected actually cover what it paid out in claims?
- Which vehicle types and customer segments generated the most claims?
- Were any pockets of the business consistently profitable?
- How did performance trend across 2014–2018?

## Key Insights

- Across five years, EIC brought in **$4.0B** in premiums against **$9.2B** paid out in claims — a gap that never closed.
- The overall premium-to-claims ratio sat at just **44%**, meaning claims routinely ran more than double what was collected in premiums.
- The company only turned the ratio positive **once** — in Q2 2018 — far too late to change its trajectory.
- Motorcycles and trucks made up the bulk of policies sold, but weren't necessarily where the money was made.
- Interestingly, niche **agricultural segments** — despite low policy volumes — were among the few consistently profitable areas of the book.

## Inside the Dashboard

- **Year filter (2014–2018)** to slice every visual dynamically
- **KPI cards** tracking total premiums, total claims, and average values per policy
- **Policy breakdown** by vehicle type, usage segment, and manufacturer
- A **gender-based claims split** showing who filed more claims
- A **profitability heatmap** across usage categories over five years
- A **premium vs. claim scatter plot** to spot outlier policies at a glance

## Skills Demonstrated

- **Power BI** - report design, layout, and storytelling
- **DAX** - custom measures for ratios, averages, and KPIs
- Conditional formatting to make loss/profit patterns pop visually
- Data modeling on raw policy-level records (premiums, claims, vehicle attributes, usage type)

## Data Snapshot

The underlying dataset is policy-level, with fields including insured value, premium, product year, vehicle type, make, usage category, and claims paid — allowing the analysis to go well beyond top-line numbers into segment-by-segment behavior.

## Takeaway

Numbers rarely lie, and EIC's is a case study in what happens when pricing doesn't keep pace with risk. This dashboard turns five years of raw policy data into a clear narrative — showing not just *that* the business struggled, but precisely *where* and *why*. It's a reminder of how much a well-built dashboard can reveal about the mechanics behind a company's decline.
