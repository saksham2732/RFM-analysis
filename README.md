# RFM Analysis and Customer Segmentation with K-Means Clustering

## Introduction

This project demonstrates an RFM (Recency, Frequency, Monetary) Analysis combined with K-Means Clustering to analyze and segment customers based on their purchasing behavior. 

RFM analysis is a widely used method in database marketing and direct marketing, especially in retail and professional services, to evaluate customer value and behavior.

### What is RFM?

  Recency:How recently a customer made a purchase.
  
  Frequency: How often a customer makes a purchase.
  
  Monetary Value: The total amount a customer has spent.

The primary objective of this analysis is to segment customers into distinct categories—Platinum, Gold, and Silver—based on their purchasing behavior. 
This segmentation helps businesses prioritize high-value customers, optimize marketing efforts, and enhance customer retention strategies.

## Project Overview

In this project, I applied RFM analysis to customer transaction data, followed by unsupervised machine learning techniques, specifically K-Means Clustering, to further refine customer segments.

### Key Steps in the Analysis

1. Data Preprocessing: Imported and cleaned the dataset to ensure accurate analysis.
  
2. RFM Calculation:

3. Scoring and Segmentation: Assigned scores to each RFM component and combined them to segment customers.

4. K-Means Clustering:
    - Applied the K-Means algorithm to the RFM scores to automatically group customers into clusters.
    - Elbow Method: Used the Elbow method to determine the optimal number of clusters by analyzing the within-cluster sum of squares.
  
5. Visualization: Used various plots to visualize the distribution of RFM scores, the resulting customer segments, and the clustering results.

## K-Means Clustering and Elbow Method

To enhance the segmentation, I used the K-Means Clustering algorithm, an unsupervised machine learning technique that groups customers into clusters based on their RFM scores. The Elbow Method was employed to determine the optimal number of clusters by plotting the within-cluster sum of squares against the number of clusters. This method helps identify the point at which adding more clusters does not significantly improve the clustering performance, ensuring a balance between model complexity and accuracy.

## Results

The analysis revealed that customers with a total RFM score of 3, 4, or 5 exhibited the highest monetary value, making them particularly valuable to the business. 

The K-Means clustering further refined these segments, identifying distinct groups of customers with similar purchasing behaviors. These clusters provide deeper insights for targeted marketing strategies.

## Conclusion

This combined RFM and K-Means Clustering analysis provides actionable insights into customer behavior, allowing for more targeted marketing strategies and improved customer relationship management. 

By focusing on the most valuable customer segments, businesses can allocate resources more effectively and drive higher returns.
