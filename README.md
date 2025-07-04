Introduction
          Customer segmentation is a powerful marketing technique that helps businesses understand and cater to different customer groups. In this analysis, we examine a mall customer dataset 
containing demographic and spending habit information to identify meaningful customer segments. By employing unsupervised machine learning techniques - specifically K-Means clustering with 
Principal Component Analysis (PCA) - i am aim to discover natural groupings within the customer base that can inform targeted marketing strategies and business decisions.

Data Exploration
          I begin by loading the dataset and visualizing key features such as Annual Income and Spending Score. This initial exploration helps us understand the distribution and relationships 
within the data.

Dimensionality Reduction with PCA
          To simplify the data and enhance clustering performance, I am apply Principal Component Analysis (PCA). This technique reduces the dimensionality of the dataset to two principal 
components, capturing the most significant variations while facilitating visualization.

K-Means Clustering and Evaluation
          Implementing the K-Means algorithm to segment customers into clusters. Using the Elbow Method, determineing the optimal number of clusters, which is found to be five. The clustering 
quality is assessed using the Silhouette Score, yielding a score of 0.45, indicating moderate clustering quality.

Conclusion
          The K-Means clustering analysis successfully identified distinct customer segments, providing valuable insights for targeted marketing efforts. While the clustering quality is 
moderate.
