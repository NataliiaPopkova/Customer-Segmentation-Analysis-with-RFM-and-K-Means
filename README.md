# 🛍 Customer Segmentation Analysis with RFM and K-Means

This project explores customer segmentation using **RFM (Recency, Frequency, Monetary)** analysis and **K-Means clustering** on the [Online Retail II dataset](https://archive.ics.uci.edu/dataset/502/online+retail+ii). The analysis focuses on British customers and aims to derive actionable business insights from transaction-level data.
---

* * *
This is a work in progress that will be updated regularly as I get more ideas. 
I chose this dataset to explore it in depth, to learn more on clustering techniques, customer analytics and how business can get insights from data using ML. 

## 📦 Project Structure

- **0. Cleaning and EDA.ipynb**  
  Initial cleaning, deduplication, handling cancellations, and basic exploratory data analysis (EDA) on transaction data.

- **1. RFM and KMeans.ipynb**  
  Creation of RFM features, scaling, KMeans clustering, silhouette and Calinski-Harabasz evaluation, centroid extraction and 3D cluster visualization.

- **2. UK_Clusters_in_detail.ipynb**  
  In-depth analysis of clusters, purchase patterns by month, top products per cluster, and first steps toward customer behavior profiling.

---

## 📊 Methods Used

- Data Cleaning and Feature Engineering (Pandas)
- RFM Feature Generation
- KMeans Clustering and Evaluation (Silhouette, Davies-Bouldin, CH Index)
- Cluster Profiling and Business Naming
- Visualizations with Plotly Express
- Product-level Analysis per Segment

---

## 🧠 Initial Findings

- **3 meaningful customer segments** identified:  
  `Loyals`, `Regulars`, and `Occasionals`, based on behavior and spending patterns.
- `Regulars` are the largest group and generate the highest total revenue despite moderate per-customer spending.
- `Loyals` represent a small group with exceptional frequency and monetary value — ideal VIP targets.
- `Occasionals` are low-engagement, low-spending customers with high recency — reactivation potential.

---
![newplot](https://github.com/user-attachments/assets/d0b85b21-7334-4006-8e70-6d6271cfdf4d)



## 🛠️ Future Work

✔ Optimize and compare **KMeans** with other clustering models:  
&emsp;— DBSCAN, Agglomerative Clustering, Gaussian Mixture Models

✔ Deeper behavioral insights via:  
&emsp;— **Temporal patterns**, **weekday/monthly trends**, **category-level analysis**

✔ Build **Tableau dashboards** and deploy a lightweight **Streamlit app**  
&emsp;to classify new customers based on RFM input

✔ Extend segmentation to **non-UK customers** and compare behavior across countries

✔ Apply **NLP to product names** to categorize purchases semantically

---

## 📁 Dataset

**Online Retail II**  
- Transactions from 2009–2011  
- Contains invoices, customer IDs, item descriptions, quantities, prices, and country

[UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/502/online+retail+ii)

---

## 💬 Author

*This project is part of my Data Science & ML journey. I'm especially passionate about applied ML for real-world decision-making and customer analytics.*  
Let’s connect on [LinkedIn](https://www.linkedin.com/in/nataliia-popkova) or feel free to explore the code and leave feedback!

---
