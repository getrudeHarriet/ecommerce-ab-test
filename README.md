## E-Commerce A/B Testing and Customer Behavior Analysis
## Executive Summary

This project simulates an A/B test for an e-commerce platform to determine whether a new feature improves conversion rates and revenue compared to the existing setup. Using a combination of SQL, Python, and statistical testing, I evaluated customer behavior across control and treatment groups, segmented by device type. While the treatment group showed a slight performance improvement, results were not statistically significant, emphasizing the need for larger sample sizes and refined experiments. The analysis demonstrates end-to-end skills in data simulation, statistical analysis, and actionable business recommendations.

## Tools & Technologies

Python: pandas, SciPy, Seaborn, Matplotlib

SQL: exploratory analysis using ipython-sql

Jupyter Notebooks: interactive analysis and documentation

VS Code: development environment

## Project Workflow
### 1. Data Simulation & Exploration

Simulated realistic e-commerce transaction and clickstream data.

Performed SQL-based exploratory analysis to calculate conversion rates, average revenue, and session times.

Segmented customers by device type to compare engagement and conversion.

### 2. Statistical Testing

Chi-Square Test → compared conversion rates between control and treatment groups.

Independent t-test → assessed differences in mean revenue.

95% Confidence Intervals → measured the precision and reliability of estimates.

### 3. Visualization & Insight Generation

Created bar charts with confidence intervals for group conversions.

Visualized revenue distributions with boxplots.

Highlighted drop-off points in the funnel to uncover optimization opportunities.

## Sample Outputs

Conversion Rate by Group


Revenue Distribution by Group


(Add your generated charts into an /images folder and update paths as needed.)

## Key Findings

The treatment group showed slightly higher conversion and revenue, but differences were not statistically significant (p > 0.05).

Conversion rates were consistently low across both groups, emphasizing the need for funnel optimization.

Device-level analysis revealed behavioral differences that could inform personalized UX improvements.

## Recommendations

Increase sample size to improve the power of statistical tests.

Refine and iterate on the feature before a full rollout.

Consider segment-specific experiments (e.g., by device type) to target improvements more effectively.

## How to Run This Project

Clone this repository

Open in VS Code or Jupyter Lab

Run notebooks in the following order:

1_data_simulation.ipynb

2_sql_queries.ipynb

3_ab_testing_stats.ipynb

## Author
Getrude Harriet Isaisi
Aspiring Data Scientist | Python | SQL | Statistics




