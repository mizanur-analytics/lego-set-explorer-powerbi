# LEGO Set Explorer 
## Project Background
The LEGO Set Explorer project was designed to build a custom, interactive analytics tool that helps users discover LEGO sets based on price, age suitability, theme, and complexity.
The goal is to transform raw LEGO product data into an intuitive dashboard that supports product comparison, affordability analysis, and customer-centric decision making.
## Dashboard Used
•	Power BI Desktop
•	Data Modeling & DAX Measures
•	Interactive Visuals, Parameters, Tooltips & Bookmarks
## Data Structure
## Data Source:
•	lego_sets.csv
## Key Preparation Steps:
•	Removed unnecessary fields: minifigs, bricksetURL, thumbnailURL
•	Verified data types for price, age, pieces, and year
•	Filtered out records missing:
o	Price
o	Age
o	Number of pieces
o	Image URL
## Derived Columns Created:
•	Age Range:
o	1–4
o	5–9
o	10–17
o	Over 18
•	Price Range:
o	$, $$, $$$, $$$$, $$$$$
## Core Measures (DAX):
•	Total Sets
•	Total Theme Groups
•	Average Age
•	Average Price
•	Average Pieces
## Questions (KPIs)
•	How many LEGO sets are available after cleaning?
•	What is the average price and complexity of sets?
•	Which themes and age groups dominate the catalog?
•	How does price vary across age ranges and themes?
•	What sets are available under a user-defined budget?
## Process
1.	Connected Power BI to the LEGO dataset
2.	Cleaned and filtered incomplete records
3.	Created calculated columns for age and price segmentation
4.	Built DAX measures for summary metrics
5.	Designed dashboard layout with cards, tables, and slicers
6.	Added interactivity:
o	Price range parameter
o	Tooltips with product images
o	Reset filters using bookmarks
o	Multi-page navigation with decomposition tree

## Dashboard
## Main Dashboard Components:
•	KPI Cards: Total Sets, Avg. Pieces, Avg. Price
•	Slicers: Theme Group, Theme, Age Range
•	Interactive Table:
o	Set Name
o	Set ID
o	Theme
o	Age Range
o	Average Pieces
o	Average Price
o	Price Range
•	Product Detail Section:
o	Image
o	Price
o	Year
o	Pieces
o	Age Recommendation
(Dashboard Screenshot Placeholder)

## Executive Summary – Key Findings
## Overview of Findings
•	LEGO sets vary significantly in price and complexity across age groups
•	Adult (18+) sets generally contain more pieces and fall into higher price ranges
•	Mid-priced sets ($$$) represent the largest portion of the catalog
## Sales & Product Trends
•	Younger age groups are dominated by lower-priced, lower-piece sets
•	Premium pricing is strongly correlated with theme specialization and piece count
## Product Performance
•	Certain theme groups consistently offer better value (higher pieces per dollar)
•	Budget-constrained users benefit from the Max Price parameter for filtering

## Project Insights / Deep Dive
•	Quantified Insight:
Premium sets (>$100) contain significantly higher average piece counts, indicating a clear price-to-complexity relationship.
•	Business Metric Impact:
Age segmentation helps retailers target customers with appropriate pricing strategies.
•	Trend Story:
LEGO has increasingly expanded high-complexity, adult-focused sets, suggesting a shift toward enthusiast and collector markets.

## Final Conclusion & Recommendations
## Conclusion
The LEGO Set Explorer successfully converts raw product data into a user-driven analytics experience, enabling informed decisions through interactivity and visual storytelling.
## Recommendations
•	Retailers can use similar dashboards for pricing and product mix optimization
•	Adding customer reviews or sales data would enhance predictive insights
•	The model can be extended to e-commerce or inventory analytics use cases
