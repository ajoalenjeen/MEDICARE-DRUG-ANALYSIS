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

![image alt](https://github.com/ajoalenjeen/MEDICARE-DRUG-ANALYSIS/blob/2d62c3fe6b99290a703dad8e11fbd71ceaf81c9d/image/Screenshot%202025-11-16%20130527.png)

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



Eliquis (Apixaban) is the #1 Medicare drug by total spending every year—reaching over $18B in 2023.

Other consistently high-spend drugs include:
Xarelto, Revlimid, Trulicity, Jardiance, Januvia, and Ozempic.

GLP-1 diabetes drugs (e.g., Ozempic) show extremely rapid growth, with spending more than doubling in 2023.

Several drugs show declining trends (e.g., Revlimid) due to generic competition.

Interpretation:
A small set of chronic cardiovascular and diabetes medications dominates Medicare spending. Demand for GLP-1 drugs is now one of the fastest-growing cost drivers in the system.


