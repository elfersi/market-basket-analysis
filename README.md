# market-basket-analysis

## Overview

This project analyzes consumer purchasing behaviour using transactional retail data and association rule mining.

The analysis combines Orange Data Mining for exploratory analysis with Python for advanced association rule extraction using the Apriori algorithm.

## Objectives

* Identify frequent product combinations and meaningful association rules.
* Evaluate associations using support, confidence and lift.
* Compare Orange Data Mining and Python for association rule mining.
* Analyze how selected product associations evolve over time.

## Methodology

The transactional data was cleaned and transformed into a basket format, with products represented using a binary encoding.

Python was used with **pandas** and **mlxtend** to perform frequent itemset mining and association rule analysis.

The **Apriori algorithm** was selected for its transparency and interpretability. A monthly analysis was also conducted to investigate temporal variations in product associations.

## Key Findings

The analysis identified recurring product combinations, with products such as whole milk, yogurt, rolls and buns, and vegetables among the most frequent items.

Some associations showed relatively low support but high lift, demonstrating that support, confidence and lift should be considered together when evaluating relationships between products.

The temporal analysis showed that association strength can vary across months, providing insights into changing purchasing patterns and potential seasonal effects.

## Business Applications

The results can support:

* Product placement
* Cross-selling strategies
* Product bundling
* Targeted promotions
* Inventory planning
* Recommendation strategies
* Analysis of seasonal purchasing patterns

## Tools & Technologies

* Python
* pandas
* mlxtend
* Jupyter Notebook
* Orange Data Mining
* Apriori
* Association Rule Mining

## Project Structure

```text
market-basket-analysis/
│
├── Market Basket Analysis - Final Research Report
├─ Market_Basket_Analysis.ipynb
└── README.md
```

