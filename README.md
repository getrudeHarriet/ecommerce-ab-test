# E-Commerce A/B Testing and Customer Behavior Analysis

This project evaluates the results of a simulated A/B test for an e-commerce platform, aiming to determine whether a newly introduced feature (treatment) improves conversion rates and revenue compared to the existing setup (control).
It also investigates customer behavior patterns, including differences by device type.

## Tools and Technologies
- Python: Pandas, SciPy, Seaborn, Matplotlib

- SQL: via ipython-sql for querying

- Jupyter Notebooks for interactive analysis

- Visual Studio Code for development

## Project workflow
### 1. **SQL-Based Exploratory Analysis**
- Calculated conversion rate by group

- Measured average revenue by group

- Analyzed session time by device

- Compared conversion rate by device

- Computed revenue per second by group

### 2. **Statistical Testing**
- Chi-Square Test → compared conversion rates between control and treatment

- Independent t-test → assessed difference in mean revenue

- 95% Confidence Intervals → evaluated the precision of estimates

### 3. **Visualizations**
- Bar chart with confidence intervals for conversion rates

- Boxplot showing revenue distribution by group

## Key Insights
- Treatment group showed slightly higher conversion and revenue compared to control.

- Statistical tests indicate differences were not statistically significant (p-values above 0.05).

- Visuals confirm most users did not convert, highlighting the need for further funnel optimization.

- Recommendation: Increase sample size or refine the feature before full rollout.

---

## Author
*Getrude Harriet Isaisi - Aspiring Data Scientist | Python | SQL | Statistics*

---

## How to Run This Project
1. Clone the repo
2. Open in VSCode or Jupyter Lab
3. Run notebooks in order:
   - '1_data_simulation.ipynb'
   - '2_sql_queries.ipynb'
   - '3_ab_testing_stats.ipynb'



