# CryptoClustering
In this challenge, Python and unsupervised learning techniques were used to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.

# Steps
1. View Market Data
![market_data](Images/market_data.png)

2. Find the best value for k-means by using the original data
![elbow_curve](Images/elbow_curve.png)
The best value for k when using the original data is 4.

3. Cluster the cryptocurrencies with K-means using the original scaled data
![market_scaled_plot](Images/market_scaled_plot.png)

4. Optimize clusters with Principal Component Analysis (PCA) 
* The total explained variance ratios: 89%

5. Find the best value for k by using the PCA data
![elbow_curve_pca](Images/elbow_curve_pca.png)
The best value for k when using the PCA data is 4.

6. Cluster the cryptocurrencies with k-means using the PCA data
![market_pca_plot](Images/market_pca_plot.png)

7. Visualize and Compare the Results
![elbow_curves_comparison](Images/elbow_curves_comparison.png)
![plot_charts_comparison](Images/plot_charts_comparison.png)

# Results
  * The best value for k was 4 for both cases. 

  * Using fewer features in K-Means clustering can make it easier to understand the groups in the data. However, this might oversimplify the information and leave out important details. So, while it makes the analysis simpler, it may not show all the intricacies and complexities in the original data.