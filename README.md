# Retail Customer Behavior Analysis — Online Retail UK

A full retail analytics project covering the key metrics and techniques 
used in real ecommerce and retail environments.

**Dataset:** [UCI Online Retail](https://archive.ics.uci.edu/dataset/352/online+retail) 
— 541,909 transactions from a UK-based gift shop between Dec 2010 and Dec 2011.

## Notebooks

| # | Notebook | Topics |
|---|---|---|
| 01 | [EDA Overview](01_eda_overview.ipynb) | Revenue, AOV, LTV, top products, seasonality |
| 02 | [Cohort Analysis](02_cohort_analysis.ipynb) | Customer retention by cohort |
| 03 | Churn Analysis *(coming soon)* | Churn rate, at-risk customers |
| 04 | A/B Testing *(coming soon)* | Statistical significance, conversion comparison |
| 05 | Market Basket Analysis *(coming soon)* | Product associations, cross-sell |

## Key Findings so far

- £8.9M total revenue across 4,338 unique customers over 12 months
- Strong Q4 seasonality — November peak at £1.16M
- Dec-2010 cohort shows the strongest retention (~35-40% monthly)
- All cohorts lose 60-80% of customers after month 1

## Stack
Python · pandas · matplotlib · seaborn · SQL

![Monthly Revenue](monthly_revenue.png)
![Cohort Heatmap](cohort_heatmap.png)
