# K-Means-Cluster-analysis 
Use K-means clusters to compare the impact of BMI and schooling years on Life expectancy between developed and developing countries
# Project Overview
Use K-means clusters to identify subgroups within developed and developing countries based on BMI & schooling years and its relationship with life expectancy.
# Research question
What do the clusters inform us in terms of Life expectancy, Schooling years and BMI at the aggregate level?
Within each cluster what is the max, min, mean, and standard deviation of life expectancy, BMI, and schooling and which countries are driving it?
# Methodology
K- means cluster to identify clusters within the given dataset
Elbow and Silhoutte methods to identify number of appropriate clusters based on the data variance
# Key findings
Both Elbow and Silhoutte methods gave two clusters namely 0 and 1.
Cluster 0 has both developed and developing economies whereas cluster 1 has only developing economies
Cluster 0 has countries majorly under overweight category and cluster 1 has countries under normal weight category
BMI and life expectancy showed inverse relationship in cluster 0. However, there are countries like Malta and Syrian Arab Republic which exhibit different life expectancy for same BMI. Also even though Malta has higher BMI than Chile, has higher life expectancy than Chile.
Over the 15 years, the mean life expectancy increased by 1.56 years for developing countries and 3.08 years for developed countries. BMI and schooling years increased by 0.8 & 0.9  respectivley for developing countries while 0.3 and 0.67 respectively for developed countries.
# Tools Used
Python|Pandas|Matplotlib.Pyplot|Seaborn|Sklearn
# How to Run
Jupyter Noetbook K-Means Cluster Project
