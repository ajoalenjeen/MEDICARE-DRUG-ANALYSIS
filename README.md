# MEDICARE-DRUG-ANALYSIS

## Project Overview

This project analyzes Medicare drug spending from 2019 to 2023, using publicly available CMS datasets. The goal is to understand where Medicare’s drug dollars are going, identify cost drivers, and uncover trends in pricing, utilization, and manufacturer concentration.

## Dataset link

https://data.cms.gov/search?keywords=drug+spending&sort=Relevancy

## Key questions explored:

* Size: What is total spend by year and drug? By manufacturer?
* Price: How is the price of Medicare drugs changing over time?
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

![image alt](https://github.com/ajoalenjeen/MEDICARE-DRUG-ANALYSIS/blob/bf00d2e98f31830bb88f91ce6f7ce356a08f58ec/image/Screenshot%202025-11-16%20130848.png)

Eliquis (Apixaban) is the #1 Medicare drug by total spending every year—reaching over $18B in 2023.

Other consistently high-spend drugs include:
Xarelto, Revlimid, Trulicity, Jardiance, Januvia, and Ozempic.

GLP-1 diabetes drugs (e.g., Ozempic) show extremely rapid growth, with spending more than doubling in 2023.

Several drugs show declining trends (e.g., Revlimid) due to generic competition.

Interpretation:
A small set of chronic cardiovascular and diabetes medications dominates Medicare spending. Demand for GLP-1 drugs is now one of the fastest-growing cost drivers in the system.

#### Price: How is the price of Medicare drugs changing over time?

![image alt](https://github.com/ajoalenjeen/MEDICARE-DRUG-ANALYSIS/blob/71272fcb6a1b104606ad040bfab1d7709494cd04/image/Screenshot%202025-11-16%20133716.png) ![image alt](https://github.com/ajoalenjeen/MEDICARE-DRUG-ANALYSIS/blob/71272fcb6a1b104606ad040bfab1d7709494cd04/image/Screenshot%202025-11-16%20133728.png) ![image alt](https://github.com/ajoalenjeen/MEDICARE-DRUG-ANALYSIS/blob/71272fcb6a1b104606ad040bfab1d7709494cd04/image/Screenshot%202025-11-16%20133737.png)

Drug prices in Medicare Part D show a clear upward trend from 2019 to 2022, with the median price per dose, price per claim, and price per beneficiary all increasing over time. Each metric peaks in 2022, followed by a modest decline in 2023, suggesting the combined effects of generic competition, policy pressure, and shifting utilization patterns. Overall, drug pricing remains on an upward trajectory despite this recent moderation.

![image alt](https://github.com/ajoalenjeen/MEDICARE-DRUG-ANALYSIS/blob/71272fcb6a1b104606ad040bfab1d7709494cd04/image/Screenshot%202025-11-16%20133756.png)

Year-over-year analysis highlights a subset of drugs with extremely high 2022 → 2023 price inflation, largely concentrated among older generic injectables affected by supply or manufacturing disruptions. At the same time, the list of the most expensive drugs in 2023 is dominated by high-cost biologics and rare-disease treatments, many exceeding $30,000 per dose. These findings indicate that while broad price levels have stabilized slightly, specific categories—particularly specialty and injectable drugs—continue to experience sharp increases.

#### Mix: What is the brand vs. generic share and how is it shifting?

Share of Total Spending

* Brand share rose from 88.3% → 90.6%

* Generic share fell from 11.7% → 9.4%

This shift reflects increased use of high-cost branded therapies and relatively slow growth in generic spending.


Substitution Ratio (Generic Claims ÷ Brand Claims)

Patients consistently used more generic claims than brand claims, with a stable substitution ratio (>1).
However, despite this high generic utilization:

* Generics account for <10% of spending, because their unit prices are much lower.


Price Gap Between Brand and Generic Drugs (Statistical Test)

A two-sample t-test comparing price per dose (PPD) shows:

*Brand drugs are significantly more expensive

    t-statistic = 14.23, p < 1e-45

This confirms that branded products cost far more per unit than generics — explaining why brand drugs dominate spending even when generic usage is high.


Brand vs. Generic Spending Trends (2019–2023)




