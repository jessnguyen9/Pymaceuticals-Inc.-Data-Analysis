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
* Duplicates: Removed any duplicate entries to maintain data integrity.
2. **Data Manipulation**
* Merging Datasets: Combined the mouse metadata and study results using the Mouse ID to create a unified dataset for analysis.
* Grouping: Grouped the data by drug regimen to generate summaries like mean, median, and standard deviation for tumor volume.
## Data Analytics
After cleaning and preparing the data, several key analyses were performed:
1. **Tumor Volume Distribution:** A box plot was generated to compare the distribution of tumor volumes across different drug regimens. This plot reveals that regimens like Capomulin and Ramicane resulted in lower tumor volumes compared to others like Infubinol and Ceftamin, suggesting that these two drugs may be more effective in reducing tumor size.

![Box Plot Tumor Volume Distribution by Drug Regimen](https://github.com/user-attachments/assets/10ecfad9-913c-483d-ac41-0df533b61db5)

2. **Correlation Between Mouse Weight and Tumor Volume:** The analysis shows a positive correlation between mouse weight and tumor volume, indicating that heavier mice tend to have larger tumor volumes. This could be due to biological factors such as metabolism or drug absorption rates, which may influence tumor growth.

![Correlation and Linear Regression of Mouse Weight vs  Average Tumor Volume (Capomulin Regimen)](https://github.com/user-attachments/assets/e1774d1a-e3ad-43ac-b36e-19be8f80247b)

3. **Drug Regimen Popularity:** A bar chart was created to compare the number of mice observed for each drug regimen. Capomulin and Ramicane were the most frequently used, indicating their popularity and potential effectiveness, followed by Infubinol and Ceftamin.

![Bar Chart Observed Mouse Timepoints by Drug Regimen](https://github.com/user-attachments/assets/6057038e-133a-476c-abc4-97ebb01adda5)

## Statistical Summary of Drug Regimens:
The following table summarizes key statistical metrics (mean, median, variance, standard deviation, and SEM) for each drug

![Untitled spreadsheet - Sheet2](https://github.com/user-attachments/assets/f55900fd-850d-49ea-aaf4-6a895e5f3eea)
 regimen:

