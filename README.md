## Telecommunications-Operator-Efficiency-Analysis
Executive Summary
This project conducts a comprehensive statistical evaluation of operator performance in the telecommunications sector, analyzing key operational metrics to identify efficiency and inefficiency patterns.

📊 Methodology
Data Preparation:

Integration of customer datasets and call records

Data cleaning and transformation (dates, operator IDs)

Handling of null values and duplicates

Exploratory Analysis:

Metric aggregation by operator: call volume, average duration, dropped call rate

Creation of derived variables for efficiency evaluation

Operator Classification:
Three categories established based on statistical criteria:

Effective: Drop rate <5% and absolute losses ≤20

At Risk: Rate 5-10% or losses >20

Highly Ineffective: Rate >10% or losses >50 with low volume

📈 Key Results
Operator Distribution:

32.1% (351 operators) classified as "Highly Ineffective"

Remaining 67.9% distributed between "Effective" and "At Risk"

Statistical Findings:

Shapiro-Wilk test confirmed non-normal data distribution

Mann-Whitney U test revealed significant differences (p<0.05) in drop rates between groups

High-volume operators showed lower relative drop rates but higher absolute impact

🔍 Actionable Insights
Precise Segmentation: 32.1% of operators identified require priority intervention

Targeted Training: "At Risk" group can improve with specific programs

Resource Optimization: Strategic reassignment based on objective metrics

🛠 Technologies Used
Python (pandas, scipy, matplotlib, seaborn)

Non-parametric statistical analysis

Data visualization

Hypothesis testing

This analysis provides a solid quantitative foundation for decision-making in service quality improvement and human resource optimization in the telecom sector.
