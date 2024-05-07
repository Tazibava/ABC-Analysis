# ABC Analysis with Power BI
## Overview
This repository contains an analysis of ABC categorization using Power BI. ABC analysis is a technique used to categorize items based on their importance, typically used in inventory management and sales analysis. The analysis aims to classify SKUs (Stock Keeping Units) into three categories: A, B, and C, based on their contribution to total sales.
## Analysis Process
### Data Preparation:
The analysis utilizes sales data from the 'Past Orders' table and 'Stock' table , which includes information about SKU IDs and corresponding sales figures.
Ensure that the data is clean and properly structured before importing it into Power BI.

### Calculation of Cumulative Sales:
Calculate the cumulative sales for each SKU, which is essential for determining the ABC categories.
Utilize DAX (Data Analysis Expressions) functions in Power BI to perform this calculation efficiently. 

### ABC Categorization:
Categorize SKUs into A, B, or C based on their contribution to total sales.
Define thresholds or criteria to classify SKUs into each category. In this analysis, we use cumulative percentage of total sales to determine the categories.

### Visualization:
Visualize the ABC analysis results using an area chart in Power BI.
Customize tooltips to display detailed information about SKUs categorized as A, B, or C when hovering over different areas of the chart.

### GitHub Repository:
This repository contains the Power BI file (.pbix) showcasing the ABC analysis.
Additionally, it includes relevant documentation, such as this README file, to provide insights into the analysis process.

## Dashboard Image:
![Inventory Analysis](https://github.com/Tazibava/ABC-Analysis/assets/166983934/457179fc-6753-4169-85ff-93757d071611)
