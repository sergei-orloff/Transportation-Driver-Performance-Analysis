# Transportation-Driver-Performance-Analysis
Analysis of trucking company data.

Medium.com publication:

https://medium.com/@serorl0v/ranking-and-optimization-in-analytics-practical-examples-b790f088e426

https://medium.com/@serorl0v/box-plot-pitfalls-e757c380eb76

________________________________________________

This document details a data analysis project focused on driver performance within a trucking company, AIDispatcher, Inc. The project aims to uncover relationships between driver performance metrics and financial outcomes.

Key Objectives:
Identify correlations between fuel efficiency, miles driven, earnings, workdays, and performance scores.
Use real operational data and statistical techniques to reveal patterns.
Inform decision-making and improve operational efficiency and driver evaluation.
Data and Methodology:
Weekly raw data on driver performance metrics is collected, cleaned, and aggregated.
Analysis is performed on an aggregated dataset.
Python libraries like pandas, seaborn, numpy, and matplotlib are used.
Various statistical methods are employed, including correlation matrices (Pearson, Kendall, Spearman), heatmaps, boxplots, histograms, and scatterplots.
Outlier detection and removal techniques are applied.
Key Findings and Insights:
Strong positive correlations exist between:
Total miles driven and total gross earnings.
Average miles driven and average gross earnings.
Average workdays and average miles driven.
Average profit/loss and performance score.
Performance scores are more strongly correlated with profitability than with revenue or miles driven.
Different correlation methods reveal variations in the strength of relationships, with Spearman and Kendall being more robust to outliers and capturing non-linear associations.
Scatterplots show a positive correlation between average miles and average profit/loss, and a negative correlation between average fuel efficiency and average profit/loss.
The analysis suggests that while increasing mileage can lead to higher profits, other factors like fuel efficiency and maintenance costs must be considered.
Outliers are identified and analyzed to understand deviations from the general trends.
Implications and Recommendations:
Optimize route efficiency instead of simply maximizing mileage.
Investigate the causes of declining fuel efficiency during extended work periods.
Revise performance metrics to incentivize sustainable operational practices.
Explore the relationship between work patterns and both revenue and efficiency.
The project concludes that a multi-method approach to correlation analysis provides a comprehensive understanding of the data relationships. The findings confirm core business dynamics while highlighting nuances that might be missed by using only one correlation method.

