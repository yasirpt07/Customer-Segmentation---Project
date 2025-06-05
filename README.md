# 🌍 Clustering Countries Based on Health Indicators

## 📌 Project Overview

This project uses **Unsupervised Machine Learning** to cluster countries based on key **health indicators** such as life expectancy, health expenditure, mortality rates, and more. By applying clustering algorithms to data sourced from the **World Bank**, we aim to uncover hidden patterns that reveal similarities and disparities in public health conditions across nations.

---

## 🧠 Objective

To identify meaningful country clusters using health-related features that can help:
- Policy makers understand regional health challenges.
- NGOs and governments allocate resources better.
- Researchers study health inequality from a data perspective.

---

## 📊 Dataset Information

- **Source**: [World Bank Health, Nutrition and Population Statistics](https://databank.worldbank.org/source/health-nutrition-and-population-statistics)
- **Records**: 10,000+ (filtered for most recent years)
- **Features** (sample):
  - Country
  - Life Expectancy at Birth
  - Health Expenditure (% of GDP)
  - Infant Mortality Rate
  - Maternal Mortality Ratio
  - Birth Rate
  - Death Rate
  - Immunization Coverage
  - Population Growth
  - Physicians per 1,000 People
  - Access to Clean Water
  - Hospital Beds per 1,000
- **Target Variable**: None (Unsupervised Learning)

---

## 🔧 Technologies Used

- Python
- Pandas & NumPy
- Scikit-learn
- Matplotlib / Seaborn
- Plotly (for interactive visualizations)
- PCA / t-SNE (for dimensionality reduction)

---

## 🚀 Project Workflow

1. **Data Collection**: Extracted from World Bank DataBank
2. **Data Cleaning**: Handling missing values, selecting relevant features
3. **Feature Scaling**: Standardized features using `StandardScaler`
4. **Dimensionality Reduction**: Applied PCA for visualization
5. **Clustering**:
   - K-Means
   - DBSCAN
6. **Evaluation**: Visualized clusters using pair plots, PCA scatter, and cluster heatmaps

---

## 📁 Project Structure

