# Customer Segmentation Project

## Description
This project aims to segment customers based on their purchasing behavior and demographics. The analysis is done using unsupervised machine learning techniques.

## Project Structure
```
customer_segmentation/
├── data/
│   └── marketing_campaign.csv
├── notebooks/
│   └── customer_segmentation_analysis.ipynb
├── docs/
│   └── profiling_customer_clusters.txt
└── README.md
```

## Data
The dataset used for this analysis is `marketing_campaign.csv`, which contains information about customers.

## Methodology
The project follows these steps:
1.  **Data Cleaning and Preprocessing:** Handles missing values and performs feature engineering.
2.  **Dimensionality Reduction:** Uses Principal Component Analysis (PCA) to reduce the number of features.
3.  **Clustering:** Applies Agglomerative Clustering to segment the customers into different groups.
4.  **Visualization:** Visualizes the clusters to understand their characteristics.
