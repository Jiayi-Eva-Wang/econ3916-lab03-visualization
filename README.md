# econ3916-lab03-visualization

# Honest vs. Misleading Visualizations

## Objective
This project examines how visualization choices can change the interpretation of economic data and demonstrates techniques for creating more transparent and accurate data visualizations.

## Methodology
- Recreated **Anscombe’s Quartet** to demonstrate how datasets with similar summary statistics can have very different visual patterns.
- Calculated a **Lie Factor of 49.0** for a truncated-axis revenue chart and redesigned the visualization using a more honest scale.
- Compared four visualizations of **real average hourly earnings**, using FRED AHETPI data adjusted to 2020 dollars.
- Conducted a four-step exploratory data analysis of World Bank GDP data covering **262 economies/aggregates across 64 years (1960–2023)**, examining structure, distributions, relationships, and anomalies.
- Built an interactive honest-chart toggler that allows users to change the wage measure, time period, y-axis floor, and scale while observing changes in the Lie Factor.

## Key Findings
Anscombe’s Quartet showed that similar summary statistics can hide very different patterns in the underlying data. The truncated-axis example demonstrated how changing the y-axis can substantially exaggerate a small change, producing a Lie Factor of **49.0**. The wage visualizations also showed that choices such as time range, axis scale, and inflation adjustment can lead readers to very different interpretations of the same economic data. Overall, the project highlights the importance of examining both the underlying data and visualization design when communicating economic evidence.
