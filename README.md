# Netflix Movies and TV Shows: Exploratory Data Analysis

A comprehensive Data Analytics and Exploratory Data Analysis (EDA) project focusing on the modern Netflix streaming catalog. This repository maps the lifecycle of content updates, profiles data cleanliness, and builds production-grade interactive visual reports.

## 🛠️ Tech Stack & Libraries
* **Language:** Python 3.10
* **Data Manipulation:** Pandas, NumPy
* **Static Visualizations & Profiling:** Seaborn, Matplotlib
* **Interactive Dashboards:** Plotly Express

---

## 📊 Analytical Pipeline

### 1. Data Integrity & Missing Property Profiling
Initial data health check using a binary heatmap to visualize structural data sparsity across variables (`director`, `cast`, and `country`).

```python
# Missing Data Map Generation
sns.heatmap(df.isnull(), yticklabels=False, cbar=False, cmap='Reds')
