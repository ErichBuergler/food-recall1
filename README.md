# food-recall1

Analysis of food recalls


This analysis contains a notebook analyzing data provided by the Directorate-General for Health and Food Safety of the European Commission. This repository analyzes 649 products intended for the Swiss market. The European health authorities have recalled those products because they are contaminated or may otherwise pose a threat to health.

The notebook looks at the risk categories within those recalled products and calculates the amount of products in each risk category.

Within the highest risk category it analyzes the 15 most affected types of food. It also calculates how often organic food products had to be recalled.

A note on  risk categories

The Directorate-General for Health and Food Safety of the European Commission divides the hazard level into four categories. Among them is the category  “undecided" which I named “not categorized" for foods whose hazard level is still unclear. The "no risk" categorisation may be due to products that have been recalled as a precautionary measure and which, after closer analysis, do not pose a risk.

A note on  most affected types of food

The Analysis shows the 15 most affected food types by absolute numbers from January 2020 to June 2022.

Technical Notes

All of the analyses above are coded in Python 3.
