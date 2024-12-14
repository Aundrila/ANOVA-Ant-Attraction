# ANOVA-Ant-Attraction
This repository contains an analysis of a dataset investigating ant attraction to different types of sandwiches. The study evaluates the impact of bread types, sandwich toppings, and the presence of butter on ant behavior using statistical methodologies such as ANOVA and Tukey's HSD.

## Project Overview
Ants are known for their ability to locate food efficiently. This project explores whether different sandwich ingredients influence ant attraction. The dataset comprises 48 observations from experiments placing sandwiches near an anthill and recording ant counts.

## Objectives
- Analyze the impact of bread types, toppings, and butter presence on ant attraction.
- Test the significance of differences between groups using hypothesis testing.
- Provide insights into factors influencing ant behavior.

## Key Features and Findings
### Statistical Methods
1. Exploratory Data Analysis (EDA):
  - Data overview and summary statistics.
  - Verification of assumptions (normality, homogeneity of variances).
    
2. Hypothesis Testing:
  - One-way and two-way ANOVA to determine significant differences between groups.
  - Tukey's HSD for post-hoc analysis to identify pairwise differences.
## Key Results
- **Bread Types:** No significant effect on ant attraction.
- **Sandwich Toppings:** "Schinken-Essiggurken" attracted significantly more ants compared to other toppings.
- **Butter Presence:** Sandwiches with butter attracted significantly more ants.

## Dataset Description
The datasetincludes:

- **Ameisen:** Number of ants attracted (continuous variable).
- **Brot:** Bread type (categorical: Vollkorn, Mehrkorn, Roggen, Weißbrot).
- **Belag:** Topping type (categorical: Schinken-Essiggurken, Erdnussbutter, Hefe-Brotaufstrich).
- **Butter:** Presence of butter (categorical: ja/nein).

## Tools and Libraries
- **Programming Language:** Python
- **Libraries:** pandas, scipy, statsmodels, matplotlib

