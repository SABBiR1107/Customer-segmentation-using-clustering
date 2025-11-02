# 🧩 Customer Segmentation Using Clustering

## 📘 Project Overview
This project aims to segment customers into distinct groups based on their **spending behavior**, **income level**, and **age** using **unsupervised machine learning** — specifically **K-Means clustering**.

The insights from this segmentation can help businesses understand customer profiles better and design targeted marketing strategies.

---

## 📂 Dataset Information
**Dataset Used:** [Mall Customers Dataset (Kaggle)](https://www.kaggle.com/datasets/shwetabh123/mall-customers)  
**Source:** Kaggle  
**Attributes:**
- `CustomerID` — Unique customer identifier  
- `Gender` — Male/Female  
- `Age` — Customer’s age  
- `Annual Income (k$)` — Customer’s yearly income  
- `Spending Score (1–100)` — Customer’s spending behavior score  

---

## ⚙️ Methods and Techniques

### **1. Data Preprocessing**
- Loaded dataset and checked for missing values.  
- Selected relevant features: `Age`, `Annual Income (k$)`, and `Spending Score (1–100)`.  
- Scaled the features using **StandardScaler** for better clustering performance.

### **2. Determining Optimal Clusters**
- Applied the **Elbow Method** to find the best value of *k* by plotting WCSS (Within-Cluster Sum of Squares).  
- Used **Silhouette Score** to validate the optimal cluster count and measure cluster quality.

### **3. K-Means Clustering**
- Applied **K-Means algorithm** with the chosen `k` value (typically 5).  
- Visualized customer groups using scatter plots for 2D feature combinations.

---

## 📊 Cluster Summary

| Cluster | Key Traits | Marketing Focus |
|----------|-------------|----------------|
| **0** | Young, low income, moderate spending | Promote trendy, affordable items |
| **1** | Young, mid-income, moderate spending | Use personalized product recommendations |
| **2** | Middle-aged, mid-income, low spending | Focus on value-driven or essential products |
| **3** | Older, low income, low spending | Emphasize comfort and budget-friendly offers |
| **4** | Middle-aged, high income, moderate spending | Target with premium or luxury product campaigns |

---

## 💡 Insights
The customer base ranges from **young budget shoppers** to **affluent professionals**.  
Tailoring marketing strategies to each segment can increase engagement and improve overall sales performance.

---

## 🧠 Tools & Libraries
- **Python**
- **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn**
- **Scikit-learn**

---

## 👨‍💻 Project Completed By
**Name:** Ahsanur Rahman  
**Role:** Data Analyst / Student (Final Year)  
**Date:** November 2025  
**Institution:** Daffodil International University  

---

> *"Understanding customers through data helps businesses connect better and grow smarter."*

