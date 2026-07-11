# Customer Segmentation Using Unsupervised Learning

## DevelopersHub Corporation – Data Science & Analytics Internship

**Author:** MISWAN

---

# Problem Statement

Businesses serve customers with diverse purchasing behaviors, spending patterns, and income levels. Applying the same marketing strategy to all customers often results in inefficient campaigns and lower customer engagement.

Customer segmentation helps businesses identify groups of customers with similar characteristics and behaviors, enabling more personalized marketing strategies and improved business performance.

---

# Objective

The objective of this project is to:

- Analyze customer demographics and spending behavior.
- Identify distinct customer segments using K-Means Clustering.
- Visualize customer groups using PCA.
- Develop targeted marketing strategies for each segment.
- Generate actionable business insights.

---

# Dataset Description

The dataset contains customer information collected by a shopping mall.

## Features

| Feature | Description |
|----------|-------------|
| CustomerID | Unique customer identifier |
| Genre | Customer gender |
| Age | Customer age |
| Annual Income (k$) | Annual income in thousand dollars |
| Spending Score (1-100) | Customer spending behavior score assigned by the mall |

---

# Data Cleaning and Preprocessing

The following preprocessing steps were performed:

- Checked for missing values.
- Removed duplicate records.
- Verified dataset consistency.
- Selected relevant features for clustering.
- Applied feature scaling using StandardScaler.

---

# Exploratory Data Analysis (EDA)

Several visualizations were created to better understand customer characteristics.

## Performed Analysis

### 1. Gender Distribution
Understanding gender balance within the customer base.

### 2. Age Distribution
Examining customer age groups.

### 3. Annual Income Distribution
Analyzing income patterns among customers.

### 4. Spending Score Distribution
Understanding spending behavior.

### 5. Age vs Spending Score
Exploring age-related purchasing trends.

### 6. Income vs Spending Score
Identifying spending patterns across income levels.

### 7. Spending Score by Gender
Comparing spending behavior between genders.

### 8. Correlation Analysis
Understanding relationships among numerical variables.

---

# K-Means Clustering

## Why K-Means?

K-Means is one of the most widely used unsupervised learning algorithms for customer segmentation. It groups customers into clusters based on feature similarity.

### Features Used

- Annual Income (k$)
- Spending Score (1-100)

---

# Elbow Method

The Elbow Method was used to determine the optimal number of clusters.

### Observation

The elbow point appeared around:

## K = 5

Therefore, five customer clusters were selected.

---

# Cluster Visualization

Customer clusters were visualized using:

- Scatter Plot
- PCA (Principal Component Analysis)

These visualizations clearly showed the separation of customers into distinct groups.

---

# Silhouette Score

The Silhouette Score was calculated to evaluate clustering quality.

A higher score indicates better cluster separation and cohesion.

---

# PCA (Principal Component Analysis)

PCA was applied to reduce dimensionality while preserving maximum information.

Benefits of PCA:

- Better visualization
- Noise reduction
- Easier interpretation of clusters

---

# Customer Segments

## Cluster 0
### High Income – High Spending

Characteristics:

- Premium customers
- High purchasing power
- Strong engagement

Marketing Strategy:

- VIP memberships
- Exclusive offers
- Premium product recommendations
- Loyalty rewards

---

## Cluster 1
### High Income – Low Spending

Characteristics:

- Wealthy customers
- Low engagement

Marketing Strategy:

- Personalized campaigns
- Product recommendations
- Premium promotions
- Retargeting strategies

---

## Cluster 2
### Low Income – High Spending

Characteristics:

- Active shoppers
- Price-sensitive customers

Marketing Strategy:

- Seasonal discounts
- Bundle offers
- Cashback promotions

---

## Cluster 3
### Low Income – Low Spending

Characteristics:

- Least active customers

Marketing Strategy:

- Budget-focused products
- Awareness campaigns
- Entry-level promotions

---

## Cluster 4
### Average Customers

Characteristics:

- Balanced income and spending behavior

Marketing Strategy:

- Cross-selling
- Upselling
- Customer retention programs

---

# Business Insights

Key findings from the analysis:

1. Five distinct customer groups were successfully identified.

2. Annual income alone does not determine spending behavior.

3. Some lower-income customers exhibit significantly higher spending behavior.

4. Customer segmentation enables personalized marketing.

5. Targeted campaigns can improve customer satisfaction and increase return on investment (ROI).

---

# Model Evaluation

The clustering model was evaluated using:

- Elbow Method
- Silhouette Score
- PCA Visualization

These techniques confirmed meaningful customer segmentation.

---

# Conclusion

Customer segmentation was successfully performed using K-Means Clustering.

The Elbow Method identified five optimal customer groups, and PCA provided effective visualization of customer segments.

The results demonstrate that customers exhibit distinct spending behaviors and should be targeted using different marketing approaches.

Implementing segmentation-based marketing strategies can help businesses:

- Improve customer engagement
- Increase sales
- Enhance customer retention
- Optimize marketing expenditures

---

# Skills Gained

- Unsupervised Learning
- K-Means Clustering
- PCA Dimensionality Reduction
- Customer Segmentation
- Business Analytics
- Marketing Strategy Development
- Data Visualization
