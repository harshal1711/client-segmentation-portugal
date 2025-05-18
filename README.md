# Client Spending Pattern Analysis for XYZ

Unsupervised learning project analyzing annual spending patterns of 440 wholesale clients using K-Means and Hierarchical clustering to uncover actionable client segments and strategic recommendations for Company XYZ.

---

## Project Overview

Company XYZ is a wholesale distributor serving business clients such as retailers, restaurants, hotels, and cafés across Portugal. The management seeks to better understand the spending behavior of its 440 clients across six product categories to make strategic decisions regarding inventory, delivery optimization, and client segmentation.

This project was completed as part of an academic data science assignment and involved applying clustering techniques to identify meaningful customer segments and develop data-driven recommendations for XYZ's business strategy.

---

## Dataset Description

The dataset includes the following information for each client:
- **Channel**: Type of client – Horeca (1) or Retail (2)
- **Region**: Geographic region – Lisbon (1), Oporto (2), Other (3)
- **Fresh**: Annual spending on fresh products
- **Milk**: Annual spending on milk products
- **Grocery**: Annual spending on grocery products
- **Frozen**: Annual spending on frozen products
- **Detergents_Paper**: Annual spending on detergents and paper products
- **Delicatessen**: Annual spending on deli products

---

## Methodology

We used a clustering-based approach to segment clients based on their spending behavior:

1. **Outlier Detection**: Extremely high spenders were identified and assigned to a separate cluster to prevent skewing.
2. **K-Means Clustering**: Applied on normalized spending data (excluding outliers) to identify distinct client segments.
3. **Hierarchical Clustering**: Used as a comparative technique to verify and support K-Means findings.
4. **Visualization**: PCA and dendrograms were used for dimensionality reduction and cluster validation.

---

## Key Findings

We identified **4 client clusters** with distinct purchasing behaviors:

| Cluster | Description |
|--------|-------------|
| **1** | Suburban retailers focused on non-perishables (milk, grocery, paper) |
| **2** | Low-spending Horeca clients, likely seasonal or new businesses |
| **3** | High-spending Horeca clients focused on fresh and frozen products |
| **4** | Anomalous high-value clients across multiple categories (outliers) |

---

## Strategic Recommendations

- **Cluster 1**: Introduce bulk purchasing programs and set up regional hubs to improve delivery efficiency.
- **Cluster 2**: Offer flexible contracts and seasonal inventory adjustments to support business growth.
- **Cluster 3**: Launch premium delivery services with flexible scheduling and freshness guarantees.
- **Cluster 4**: Assign dedicated account managers and design loyalty programs to retain high-value clients.

---

## Deliverables

- `Codefile.Rmd` – Contains data exploration, preprocessing, and clustering implementation.
- `Executive Summary.pdf` – A business-facing summary of findings and recommendations for XYZ management.

---

## Team Members

- Harshal Sable  
- Abraham George  
- Aakash Patil  
- Rahma Hassan  
- Charlotte Wang  
