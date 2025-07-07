# E-Commerce A/B Testing and Customer Behavior Analysis

This project analyzes a simulated A/B testing from an e-commerce site to determine whether a new feature (treatment) leads to a higher conversion rates and revenue compared to the existing setup(control). It also explores user behavior by device  type.

## Tools and Technologies
-Python (Pandas, Scipy, Seaborn, Matplotlib)
-SQL (via ipython-sql)
-Jupyter Notebooks
-Visual Studio Code

## Key Components
### 1. **SQL Analysis**
- Conversion rate by group
- Average revenue by group
- Session time by device
- Conversion rate by device
- Revenue per second by group

### 2. **Statistical Testing**
- Chi-Square test for conversion rate difference
- T-Test for average revenue differnce
- 95% Confidence intervals

### 3. **Visualizations**
- Conversion rate bar chart with confidence intervals
- Revenue boxplot by group

## Folder Structure

## Summary of Findings
- Treatment group had a slightly higher conversion and revenue but the results were not statistically significant.
- Confidence intervals and p-values support that the observed values could be due to chance.
- Visuals confirm most users did not convert - Insights suggest more data or deeper funnel optimization may be needed.

---

## Author
*Getrude Harriet - Aspiring Data Analyst | Python | SQL | Statistics*

---

## How to Run This Project
1. Clone the repo
2. Open in VSCode or Jupyter Lab
3. Run notebooks in order:
   - '1_data_simulation.ipynb'
   - '2_sql_queries.ipynb'
   - '3_ab_testing_stats.ipynb'



