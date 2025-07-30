**Wage & Unemployment Analysis Using CPS Data (2017–2024)**

----
This project explores labor market dynamics in the United States by analyzing the Current Population Survey (CPS) data from January 2017 to December 2024. Using statistical and machine learning techniques, we examined wage inequality, gender pay gaps, industry-wise wage trends, and the impact of COVID-19 on unemployment. The findings provide actionable insights for policy makers, HR teams, and economists.

----

🧠 Key Objectives
Understand how education, industry, and gender impact wages.

Investigate gender wage disparities across industries and occupations.

Identify factors driving wage variability using machine learning.

Quantify the impact of COVID-19 on unemployment using causal inference.

----

📁 Data Source
Dataset: Current Population Survey (CPS), U.S. Census Bureau & Bureau of Labor Statistics.

Time Frame: Jan 2017 – Dec 2024

Sample Size: Over 390 variables and millions of records.

----
🔍 Methodology & Techniques
We began with thorough **data cleaning and preprocessing**, filtering for complete interviews, normalizing income fields, and engineering new features like age buckets, education levels, and industry codes. To statistically validate wage differences across groups, we applied **hypothesis testing** techniques including t-tests and ANOVA.

To uncover hidden segments in the labor force, we used **K-Means clustering** to group individuals based on occupation, experience, and industry. To model wage drivers, we employed a **Random Forest Regressor**, which provided robust predictions and allowed us to assess feature importance. Additionally, we used **feature ablation** techniques to isolate the influence of individual variables while minimizing interaction effects.

To measure the **causal effect of COVID-19 on unemployment**, we applied the CausalImpact framework, enabling us to quantify the increase in unemployment rates that could be directly attributed to the pandemic.

----
📈 Key Insights
Education drives higher wages: Statistically significant wage differences were found across education levels.

Gender pay gap persists: Men consistently earn more than women across all industries and occupations, even after clustering.

Top wage influencers: Experience, education, occupation, and industry were most predictive of income levels.

COVID-19 Impact: A 2% increase in unemployment was directly attributed to the pandemic using causal inference.

----
🧰 Tools & Technologies
Languages: Python

Techniques: Hypothesis Testing, Clustering, Causal Impact Analysis, Random Forests

Libraries: Pandas, Scikit-learn, Matplotlib, CausalImpact, NumPy

----
✅ Business Impact
This project provides a framework for:

HR teams to create data-backed compensation strategies.

Policymakers to understand the socioeconomic impact of crises like COVID-19.

Economists and researchers to quantify wage disparities and employment trends using public data.
