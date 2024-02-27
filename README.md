Cryptocurrency-Challenge

Objective:
Using Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.

Method Using to acheive the goal:
1. Preper the data
   StandardScaler() module from scikit-learn to normalize the data from the CSV file.
   Create a DataFrame with the scaled data and set the "coin_id" index from the original DataFrame as the index for the new DataFrame.

2.Find the Best Value for k Using the Original Scaled DataFrame using Elbow Method
3.Cluster the Cryptocurrencies with K-means Using the Original Scaled Data
4. Optimize Clusters with Principal Component Analysis
5. Find the Best Value for k Using the PCA Data
6.Cluster the Cryptocurrencies with K-means Using the PCA Data

Analysis:
When Analyzing the Line plots when uing PCA values intertia droping more steeper than the original data.
When analyzing the scatter plot comparing original data when using PCA components the clusters 0 & 1 are grouping more closer.





