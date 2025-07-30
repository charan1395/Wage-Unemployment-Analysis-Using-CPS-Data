📌 **CPS-Based Analysis of Wage Inequality and Unemployment Trends in the U.S**.

----
📄 **Overview**

This project explores wage disparities and labor market dynamics in the U.S. using CPS data from 2017 to 2024. Our analysis addresses five distinct research questions using techniques from clustering, causal inference, random forests, and statistical testing. The goal is to uncover meaningful insights to support HR decisions, public policy, and economic forecasting.

----
🧠 **Research Questions & Notebooks**

Is there a significant gender pay gap after accounting for job, education, and experience?
– Used hypothesis testing (t-tests) within similar role-education groups to assess wage disparity.

What are the main clusters or segments in the workforce based on wage-driving variables?
– Applied K-Means clustering to identify patterns across occupation, experience, and industry.

Which features best explain wage differences across industries?
– Built a Random Forest regression model and analyzed feature importances.

How do wage levels vary across U.S. regions and industries?
– Conducted segmented analysis across state and industry categories using EDA and statistical summaries.

What was the causal impact of COVID-19 on unemployment rates?
– Used the CausalImpact library to quantify the increase in unemployment due to the pandemic.

----
🛠️ **Methodology & Techniques**

We began by cleaning and standardizing the CPS dataset, focusing on complete interviews and reliable wage fields. Statistical techniques such as t-tests and ANOVA were used to validate group-wise differences. We used K-Means clustering to uncover structural labor force segments and trained a Random Forest Regressor to model wage influencers. To quantify the pandemic’s effect, we used Bayesian Structural Time Series with CausalImpact, measuring counterfactual unemployment trends.

----
🧰 Tools & Technologies

Languages & Libraries: Python, Pandas, NumPy, Matplotlib, Seaborn

Statistical Methods: T-tests, ANOVA, Clustering, Causal Impact, Random Forest

ML Libraries: Scikit-learn, CausalImpact (via tfcausalimpact), Yellowbrick

Domain: Labor Economics, Public Policy, Workforce Analytics

✅ **Business Impact**

This project provides a framework for:
HR teams to create data-backed compensation strategies.

Policymakers to understand the socioeconomic impact of crises like COVID-19.

Economists and researchers to quantify wage disparities and employment trends using public data.
