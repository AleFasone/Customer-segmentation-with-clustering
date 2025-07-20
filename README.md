# Customer-segmentation-with-clustering
This repository focuses on customer segmentation using clustering to enhance marketing efficiency in retail. It analyzes e-commerce data to group customers based on behavior, demographics, and more, aiming to improve customer retention, optimize pricing, and develop targeted strategies.
## Project Objectives 🚀
* To develop a robust customer segmentation model to refine marketing strategies.
* To define customer clusters, providing deep insights for personalizing offers and optimizing promotional campaigns.
* To enhance customer satisfaction and drive sustainable business growth through a customer-centric approach.
* To improve metrics such as marketing efficiency, product development, customer satisfaction, customer retention, price optimization, and strategic resource allocation.

## Key Features 💡
The analysis utilized an e-commerce dataset with 64,885 unique customers [cite: 17][cite_start], augmenting it with five engineered features to capture various dimensions of customer behavior:

* **Frequency**: Total count of different orders made by each client.
* **Recency**: Days since the last order for each client.
* **Customer Lifetime Value (CLV)**: Total value for the business of each client.
* **Average Unit Cost**: Average profitability from each order made by each client.
* **Age**: Age of the customer.

## Methodology 🔬
The customer segmentation approach involved several sequential phases:

1.  **Feature Engineering**: Preprocessing and augmentation of the original dataset with five new features, specifically engineered to capture various dimensions of customer behavior.
2.  **Optimal Cluster Determination**: Employed the Elbow Method, the Silhouette Score, and dendrogram analysis to determine the optimal number of clusters (k).
3.  **K-Means Clustering**: Once the optimal number of clusters was identified, k-means clustering was performed, and customers were assigned to their respective clusters.
4.  **Dimensionality Reduction**: Applied dimensionality reduction techniques such as PCA and t-SNE to visualize and interpret the cluster structure in lower-dimensional spaces.

## Key Results and Insights 📊

The convergence of results from the Elbow Method, Silhouette Score, and dendrogram analysis strongly indicated that a segmentation into **four clusters (k=4)** constitutes the optimal level.

**Cluster Profiles:**
* **Cluster 0**: This segment represents the youngest demographic (mean age = 46.78 years) and the most active clients, exhibiting the highest purchase frequency (mean = 20.85) and the lowest recency (mean = 3255 days). Maintaining a high average unit cost ($79.66), they also yield the highest Customer Lifetime Value (CLV) (mean = $3806.64).
* **Cluster 1**: Comprising the oldest customer population (mean age = 56.41 years), these are the least active customers, characterized by the highest recency (mean = 4184.87 days) and lowest frequency (mean = 4.39). Despite an average unit cost (mean = $62.18) similar to other clusters, they exhibit the lowest Customer Lifetime Value (mean = $643.07).
* **Cluster 2**: Customers in this cluster tend to make more frequent purchases, though with a lower average unit cost (mean = $61.78). This results in a medium Customer Lifetime Value (mean = $1185.93). Targeting these customers effectively requires focusing on lower-cost goods.
* **Cluster 3**: This cluster represents customers with the most expensive purchasing behaviors, evident from their highest Average Unit Cost (mean = $119.67) and second-highest Customer Lifetime Value (mean = $1773.30), alongside an average frequency (mean = 6.94). Identifying this segment allows the company to focus marketing campaigns on higher-value goods tailored to their preferences.

## Conclusion 📝

In conclusion, clustering analysis identified four distinct customer segments, each characterized by specific purchasing habits. Implementing this strategy is crucial for the company to adopt a truly customer-centric growth plan. These segmentation-based strategies will optimize campaign effectiveness, allocate resources more efficiently, and foster more targeted and sustainable business growth.
