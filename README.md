# KMeans Clustering for Customer Segmentation

## Project Overview
This project uses KMeans clustering on user interaction data from an online sporting goods store. The store displays rotating banners promoting products or the company. The goal is to segment users based on their behavior (clicks, purchases, etc.) and help the marketing team better target users or decide whether to monetize the banner area via external ads using the CPC (Cost-Per-Click) model.

---

## Objective
- Perform user segmentation using unsupervised learning.
- Understand the effectiveness of banners for different user clusters.
- Assist decision-making regarding external advertising partnerships.

---

## Dataset Features

| Column Name           | Description |
|-----------------------|-------------|
| `order_id`            | Unique ID for each purchase |
| `user_id`             | Unique identifier for each user |
| `page_id`             | Identifier for the page |
| `product`             | Product shown (e.g., clothes, shoes, etc.) |
| `site_version`        | Version of the website (mobile or desktop) |
| `time`                | Time of the event |
| `title`               | Type of interaction: `show`, `click`, or `order` |
| `target`              | Purchase event flag (1 if purchase occurred, else 0) |

---

## Steps Performed
- Exploratory Data Analysis
- Data preprocessing:
  - Handled categorical variables using one-hot encoding.
- Applied **KMeans clustering** and used the **Elbow method** to determine optimal number of clusters.
- Analyzed feature averages for each cluster.

---

## Dataset
https://www.kaggle.com/datasets/podsyp/how-to-do-product-analytics
(Contains 8471220 instances and 7 features)

