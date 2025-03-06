# Pymaceuticals Inc. Data Analysis
## Overview
This project analyzes the effect of various drug regimens on tumor volumes in mice. Using data from two sources: **Mouse Metadata** and **Study Results**. We perform an analysis to understand the impact of different treatments on tumor growth. Key findings are visualized using box plots, bar charts, and statistical analysis. Insights derived from the data aim to help researchers identify the most effective drug regimens for further study.
## Goals and Approach
The main goal of this analysis is to understand the relationship between drug regimens and tumor volumes, identify the most effective treatments, and summarize key statistics for each regimen. Through this process, we derive actionable insights that can inform future research decisions and drug testing protocols.
## Key Objectives:
1. Clean and merge data from two separate sources.
2. Use statistical summaries to evaluate the impact of different drug regimens on tumor size.
3. Create visual representations (box plots, bar charts) to make the analysis easier to interpret.
4. Identify key trends and provide actionable recommendations for improving drug efficacy.
## Data Acquisition
The data for this analysis is sourced from two CSV files:
* **Mouse Metadata:** Contains information about each mouse, such as its gender, weight, and drug regimen.
* **Study Results:** Contains tumor volume measurements for each mouse over time during the experiment.
## Data Preparation
1. **Data Cleaning**
* Missing Values: Identified and handled missing or incomplete data in both datasets.
* Data Type Conversion: Converted the necessary columns into appropriate data types (e.g., numeric columns for tumor volume, categorical for drug regimen).
* **Duplicates:** Removed any duplicate entries to maintain data integrity.
2. **Data Manipulation**
* **Merging Datasets:** Combined the mouse metadata and study results using the Mouse ID to create a unified dataset for analysis.
* **Grouping:** Grouped the data by drug regimen to generate summaries like mean, median, and standard deviation for tumor volume.
## Data Analytics
After cleaning and preparing the data, several key analyses were performed:
1. Tumor Volume Distribution: A box plot was generated to compare the distribution of tumor volumes across different drug regimens. This plot reveals that regimens like Capomulin and Ramicane resulted in lower tumor volumes compared to others like Infubinol and Ceftamin.

![Box Plot Tumor Volume Distribution by Drug Regimen](https://github.com/user-attachments/assets/10ecfad9-913c-483d-ac41-0df533b61db5)

3. 
