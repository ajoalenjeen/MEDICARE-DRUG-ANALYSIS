# MEDICARE-DRUG-ANALYSIS

## Project Overview

This project analyzes Medicare drug spending from 2019 to 2023, using publicly available CMS datasets. The goal is to understand where Medicare’s drug dollars are going, identify cost drivers, and uncover trends in pricing, utilization, and manufacturer concentration.

## Dataset link

https://data.cms.gov/search?keywords=drug+spending&sort=Relevancy

## Key questions explored:

* Size: What is total spend by year and drug? By manufacturer?
* Price: How is average spend per dose unit changing? Per claim? Per beneficiary?
* Mix: What is the brand vs. generic share and how is it shifting?
* Outliers: Which products trigger the outlier flag and why?
* Growth: Which drugs have the highest 2019–2023 CAGR in price-per-dose?

## Analysis

#### What is total spend by year and drug? By manufacturer?

![image alt]([https://github.com/ajoalenjeen/MEDICARE-DRUG-ANALYSIS/tree/5de82b95749124111bd881aa86dddbd99b69737a/image](https://github.com/ajoalenjeen/MEDICARE-DRUG-ANALYSIS/blob/1e6a13f52b57d630a9f2ce7711d50d43b55135a1/image/Screenshot%202025-11-16%20130527.png))

Part D spending is significantly higher than Part B, accounting for the bulk of Medicare drug expenditures.

Both programs show year-over-year growth, with Part D rising from roughly $180B in 2019 to more than $275B in 2023.

Part B spending grows more modestly—from about $38B to $50B—but still shows a clear upward trend.

Interpretation:
Growth is driven by rising utilization, higher prices for specialty drugs, and expansion of chronic-disease treatments (e.g., diabetes, cardiovascular, autoimmune therapies).


![image alt](https://github.com/ajoalenjeen/MEDICARE-DRUG-ANALYSIS/blob/19e3c62b2fecca293ccb78b29a7203e0df9c1f02/image/Screenshot%202025-11-16%20130543.png)

A small group of manufacturers dominates spending, led by:
BMS (Bristol-Myers Squibb), Novo Nordisk, Boehringer Ingelheim, Eli Lilly, and GSK.

These companies collectively account for tens of billions in spending due to blockbuster therapies in:

* Anticoagulation (e.g., Eliquis, Xarelto)

* Diabetes/GLP-1 drugs (e.g., Ozempic, Trulicity)

* Oncology

Manufacturer concentration is high and increasing, suggesting consolidation of market power among top pharmaceutical companies.

Interpretation:
Medicare spending is heavily influenced by chronic-disease drug portfolios from a few major manufacturers.
