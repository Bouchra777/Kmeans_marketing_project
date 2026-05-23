# Customer Segmentation using K-Means Clustering

Big Data & Business Intelligence project focused on customer segmentation using Machine Learning and Power BI analytics.

---

# Project Overview

This project applies Data Science, Big Data Analytics, and Business Intelligence techniques to identify customer segments based on purchasing behavior and annual income.

Using the K-Means clustering algorithm, the project transforms raw customer data into strategic business insights that can help companies:

- Improve marketing strategies
- Increase customer retention
- Personalize customer experience
- Optimize business decision-making

The final results are integrated into an interactive Power BI dashboard for executive and analytical reporting.

---

# Business Problem

Traditional customer segmentation methods often fail to capture complex purchasing behaviors.

This project answers the following business question:

> How can customer data be used to identify meaningful behavioral segments that improve marketing efficiency and business profitability?

---

# Project Objectives

- Apply a complete Big Data analytical workflow
- Implement K-Means clustering for customer segmentation
- Engineer business KPIs and strategic metrics
- Build interactive Power BI dashboards
- Generate actionable marketing recommendations

---

# Dataset

Dataset: **Mall Customer Segmentation Data**  
Source: Kaggle

Variables used:

| Variable | Description |
|---|---|
| Gender | Customer gender |
| Age | Customer age |
| Annual Income (k$) | Annual income |
| Spending Score | Customer spending score |

---

# Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Power BI
- Jupyter Notebook

---

# Machine Learning Workflow

## Data Processing

- Missing values verification
- Data cleaning
- Feature selection
- Outlier analysis
- Standardization using `StandardScaler`

## Clustering Model

Algorithm used:

```python
K-Means Clustering
```

### Optimal Clusters Selection

The **Elbow Method** was used to determine the optimal number of clusters.

Optimal value:

```text
K = 5
```

---

# Customer Segments Identified

| Cluster | Profile |
|---|---|
| Cluster 0 | Standard Customers |
| Cluster 1 | Premium Customers |
| Cluster 2 | Economical Active Customers |
| Cluster 3 | Savers |
| Cluster 4 | Low-Value Customers |

---

# Business KPIs

The project includes several business KPIs:

- Average Annual Income
- Average Spending Score
- Customer Distribution
- Segment Profitability
- Value Score

### Value Score Formula

```text
Value Score = Annual Income × Spending Score
```

---

# Power BI Dashboard

The project includes interactive dashboards with:

- Customer segmentation visualization
- KPI cards
- Scatter plots
- Cluster profitability analysis
- Executive summary views
- Strategic recommendations

---

# Strategic Recommendations

## Premium Customers

- VIP loyalty programs
- Personalized offers
- Exclusive experiences

## Savers

- Activation campaigns
- Premium product targeting

## Standard Customers

- Upselling strategies
- Seasonal promotions

## Economical Active Customers

- Budget-friendly loyalty programs
- Promotional campaigns

## Low-Value Customers

- Automated low-cost engagement

---

# Project Structure

```bash
Kmeans_marketing_project/
│
├── kmeans_marketing.ipynb
├── Mall_Customers.csv
├── Mall_Customers_Segmented.csv
├── Kmeans_marketing.pbix
└── project docs/
```

---

# Key Results

- Identification of 5 behavioral customer segments
- Improved business understanding of customer behavior
- Creation of actionable marketing insights
- Development of executive BI dashboards

---

# Academic Context

Big Data & Business Intelligence academic project focused on Machine Learning and strategic analytics. :contentReference[oaicite:0]{index=0}

---

# Author

**Bouchra El Kharrati**  
MGSI4 — ENSAO

---

# References

- Scikit-learn Documentation
- Microsoft Power BI Documentation
- Kaggle Dataset
- Marketing Management — Philip Kotler

---

# License

Educational and academic use only.
