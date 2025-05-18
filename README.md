# Customer-Segmentation-using-K-Means-Clustering_Xiteej_Wankhede
# 📦 Snapdeal Menternship Project: Customer Segmentation

Welcome to the repository for my data science project completed as part of the **Snapdeal Menternship**. This project focuses on customer segmentation using **K-Means Clustering** and **PCA (Principal Component Analysis)** to uncover actionable customer insights for personalized marketing and business growth.

---

## 🔍 Project Objective

To segment Snapdeal's customer base into distinct groups based on purchasing behavior, enabling more personalized marketing, improved retention, and increased customer lifetime value (CLV).

---

## 🧠 Approach

1. **Data Cleaning & Preprocessing**
   - Removed outliers using Z-score method
   - Feature engineering (TotalAmount, InvoiceHour)
   - One-hot encoding for categorical variables

2. **Feature Scaling**
   - StandardScaler used for normalization

3. **Dimensionality Reduction**
   - PCA applied to visualize clusters in 2D

4. **Clustering**
   - K-Means applied with `k=4` (selected using Elbow Method)

5. **Cluster Analysis**
   - Each segment profiled based on mean spend, frequency, and time of purchase

---

## 📊 Visuals Included

- 📈 **Elbow Plot** for optimal k
- 🎯 **PCA Scatter Plot** for cluster visualization
- 🧩 **Cluster-wise Summary Table** with strategy recommendations

---

## 💡 Key Insights

| Cluster | Type             | Behavior                                | Strategy                          |
|---------|------------------|-----------------------------------------|-----------------------------------|
| 0       | Standard Buyers  | Low spend, frequent                     | Promote bundles/add-ons           |
| 1       | Bulk Buyers      | High volume, price-sensitive            | Volume discounts, loyalty plans  |
| 2       | Mid Spenders     | Balanced behavior                       | Cross-sell and personalized ads  |
| 3       | Premium Buyers   | High spend, brand-driven                | VIP rewards, early access deals  |
