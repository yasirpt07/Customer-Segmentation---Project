# 🧠 Customer Segmentation Using Unsupervised Learning

### 🎯 Project Objective

This project applies **unsupervised machine learning** to segment customers based on their purchasing behavior. The goal is to help businesses personalize marketing strategies, improve customer retention, and increase profitability.

---

### 📊 Dataset Overview

- **Dataset Name**: `sales_and_customer_insights.csv`
- **Rows**: ~10,000+
- **Features**: 15 (including frequency, order value, churn probability, seasonality, etc.)
- **Source**: [Kaggle Dataset](https://www.kaggle.com/datasets/imranalishahh/sales-and-customer-insights)

---

### 🛠️ Tools & Libraries Used

- Python (Pandas, NumPy)
- Scikit-learn (KMeans, StandardScaler, PCA, Silhouette Score)
- Seaborn & Matplotlib (Visualizations)
- Power BI (Dashboard Reporting)
- Jupyter Notebook

---

### 🔍 Key Steps Performed

1. **Data Cleaning & Preprocessing**:
   - Removed duplicates and missing values
   - Treated skewness and confirmed no outliers using IQR method

2. **Exploratory Data Analysis (EDA)**:
   - Distribution analysis of Lifetime Value, Purchase Frequency, and Churn Probability
   - Region-wise behavior and seasonal buying trends

3. **Feature Selection & Scaling**:
   - Selected numerical behavioral features for clustering
   - Scaled features using StandardScaler

4. **Customer Segmentation Using KMeans**:
   - Used Elbow Method and Silhouette Score to select optimal `k=4`
   - Clusters profiled based on behavioral metrics
   - Silhouette Score achieved: **0.19**

5. **Cluster Labeling & Business Insights**:
   - Named clusters (e.g., "Loyal & High Value", "Infrequent Buyers", "Churn-Prone")
   - Interpreted behavior patterns for marketing strategy

6. **Visualization with PCA**:
   - 2D visual representation of clusters using PCA

7. **Exported Results for Reporting**:
   - Merged cluster labels with original data
   - Final dataset exported for Power BI dashboard creation

---

### 📈 Business Insights

- **Cluster 1**: Loyal & High Value — ideal for loyalty programs
- **Cluster 2**: High Frequency but High Churn — needs engagement offers
- **Cluster 3**: Low Value Fast Buyers — upsell opportunities
- **Cluster 0**: Infrequent Buyers — low-touch reactivation campaigns

---

### 📂 Outputs

- Final CSV: `clustered_customer_full_data.csv`
- Power BI-ready dataset
- Jupyter Notebook with full code and visualizations

---

### 📎 How to Run

1. Clone this repository
2. Install dependencies with:  
   `pip install pandas numpy scikit-learn matplotlib seaborn`
3. Run `customer_segmentation_Capstone_Project.ipynb` in Jupyter
4. Review the exported CSV and visual insights

---
