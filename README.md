# 🚀 Smart Clustering Engine — SQL + ML for Customer Segmentation

This project is a complete data-driven engine that segments e-commerce customers using SQL, applied statistics, and unsupervised machine learning (K-Means). It leverages RFM (Recency, Frequency, Monetary) behavioral data to discover hidden customer patterns and enable personalized marketing strategies.

---

## 🛠 Tech Stack

- **Python 3.10**
- **pandas, numpy** – data manipulation
- **seaborn, matplotlib** – data visualization
- **sqlite3** – SQL-based data exploration
- **scikit-learn** – StandardScaler, KMeans, PCA

---

## 📁 Dataset Summary

- **Recency**: Days since last purchase
- **Frequency**: Number of purchases
- **MonetaryValue**: Total amount spent by the customer  
- **Total records**: 200 synthetic customer profiles

---

## 🔍 Workflow Overview

1. **SQL Exploration**: Basic stats and value ranges via sqlite3
2. **Statistical Analysis**: Distributions and outliers with seaborn
3. **Feature Scaling**: StandardScaler applied to normalize RFM variables
4. **K-Means Clustering**: Clustering with optimal `k=10` selected via Elbow Method
5. **PCA Visualization**: 2D scatter plot to visualize cluster separation
6. **Cluster Profiling**: Mean RFM values per cluster and strategic interpretations

---

## 📈 Key Outputs

| Cluster | Insight |
|---------|---------|
| 0 | Recent buyers with high spend and moderate frequency |
| 3 | Very frequent and high-spending clients |
| 5 | Low-value, inactive customers |
| 7 | VIP clients at risk (high value but low frequency) |

---

## 🧠 Business Use Cases

- Targeted marketing per customer group
- Loyalty and churn prevention programs
- Lifetime value prediction (next step)
- CRM personalization

---

## 📦 Files Included

- `Smart_Clustering_Engine.ipynb` – Full analysis notebook
- `customer_segments_k10.csv` – Output dataset with cluster labels



## 👩🏻‍💻 Author

**Maria Almeida**  
Aspiring Machine Learning Engineer | Industrial Engineer with strong background in statistics, logistics, and business optimization

---

## 📌 Next Steps

- Automate with FastAPI for real-time segmentation
- Use clusters as features for predictive models
- Deploy with Streamlit or Flask for business teams

