# Customer Segmentation Project

## Description
This project conducts an in-depth analysis of customer data to identify distinct segments, enabling targeted marketing recommendations. The methodology primarily employs unsupervised machine learning techniques.

## Project Structure
```
customer_segmentation/
├── data/
│   └── marketing_campaign.csv
├── notebooks/
│   └── customer_segmentation_analysis.ipynb
├── .gitignore
└── README.md
```

## Data
The dataset utilized for this analysis is `marketing_campaign.csv`. This file contains comprehensive customer information, including:
- Demographic attributes (e.g., age, education level, marital status, income).
- Household composition details (e.g., number of children and teenagers).
- Purchasing behaviors (e.g., spending across various product categories).
- Responses to past marketing campaigns.

## Methodology
The analytical process is structured into the following key phases:

1.  **Data Cleaning and Preprocessing**:
    *   Identification and handling of missing data points.
    *   Feature engineering to derive new variables pertinent to customer behavior and segmentation.

2.  **Dimensionality Reduction**:
    *   Application of Principal Component Analysis (PCA) to reduce the dataset's dimensionality, thereby simplifying subsequent modeling while retaining essential data variance.

3.  **Clustering**:
    *   Implementation of Agglomerative Clustering, an unsupervised learning algorithm, to group customers into distinct, homogeneous segments based on their features.

4.  **Visualization**:
    *   Creation of various plots and charts to visually represent and characterize the identified customer clusters, facilitating interpretation and understanding of segment profiles.

## Customer Cluster Profiles and Marketing Strategies

### Cluster 0: The Established Family
*   **Customer Profile**: These customers are definitively parents, typically older, with family sizes ranging from 2 to 4 members. Their households frequently include teenagers. This segment also encompasses single-parent households.
*   **Marketing Strategy Recommendations**:
    *   **Goal**: To capitalize on convenience and value for family-oriented purchases.
    *   **Action**: Implement multi-buy discounts on common household staples and non-perishable goods (e.g., "Buy 2, Get 1 Free" offers on cereals, snacks, or cleaning supplies). Promote ready-made meal solutions or meal kits tailored for 3-4 people, emphasizing time-saving benefits for busy parents. Given their older demographic, utilize traditional marketing channels such as flyers and newspaper inserts in conjunction with digital advertising.

### Cluster 1: The Young Parent
*   **Customer Profile**: The majority of customers in this cluster are younger parents, typically with a family size of up to 3 members. They predominantly have one young child and less frequently teenagers.
*   **Marketing Strategy Recommendations**:
    *   **Goal**: To focus on products and services catering to young children, emphasizing premium quality and ease of shopping.
    *   **Action**: Highlight fresh produce sections, organic, and health-focused items for babies and toddlers. Leverage targeted social media campaigns and personalized coupons via mobile grocery applications, focusing on specific baby/toddler brands. Consider in-store experiences such as "kids eat free" sampling events or dedicated family-friendly parking spaces.

### Cluster 2: The High-Income Professional
*   **Customer Profile**: This segment consists of high-income individuals or couples without children, with an age distribution that spans across all age groups.
*   **Marketing Strategy Recommendations**:
    *   **Goal**: To promote premium, specialty, and gourmet products, focusing on higher profit margins.
    *   **Action**: Market high-end cuts of meat, imported cheeses, fine wines, and exclusive specialty/international food items. For this high-income demographic, emphasize product quality and unique consumption experiences over price discounts. Develop premium bundle kits (e.g., "Gourmet Dinner Kit") and disseminate elegant, magazine-style email newsletters showcasing new and exclusive product offerings.

### Cluster 3: The Budget-Conscious Family
*   **Customer Profile**: These customers are parents, generally older, and belong to a lower-income bracket. Their family sizes range from 2 to 5 members, often including teenagers.
*   **Marketing Strategy Recommendations**:
    *   **Goal**: To maximize savings and promote large-volume purchasing.
    *   **Action**: Prioritize marketing of store-brand/private-label products across all categories to underscore better value. Promote bulk buying options (e.g., large family-sized packages) and extensively publicize weekly circular sales. Implement a loyalty program that provides high-value points or immediate cash-off rewards to encourage repeat visits driven by essential cost savings.
