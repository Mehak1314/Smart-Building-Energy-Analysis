# 🏢 Smart Building Energy Analysis using PCA & K-Means

A data analytics and unsupervised machine learning project that explores smart building energy consumption using the ASHRAE Great Energy Predictor III dataset. The project applies data preprocessing, dimensionality reduction (PCA), and clustering (K-Means) to identify patterns in building energy usage and understand similarities between buildings.

---

# 📌 Project Overview

Modern smart buildings generate massive amounts of energy consumption data. Understanding this data helps improve energy efficiency, reduce operational costs, and support sustainable building management.

In this project, historical building energy data is analyzed to discover hidden patterns rather than predict future values. Using Principal Component Analysis (PCA) and K-Means Clustering, buildings with similar energy consumption characteristics are grouped together for better analysis.

---

# 📊 Dataset

This project uses the **ASHRAE Great Energy Predictor III** dataset available on Kaggle.

**Dataset Source**

https://www.kaggle.com/c/ashrae-energy-prediction

The dataset includes:

- Energy meter readings from 1,400+ commercial buildings
- Building metadata
- Weather information
- Multiple energy meter types:
  - Electricity
  - Chilled Water
  - Steam
  - Hot Water

---

# 🎯 Objectives

- Clean and preprocess large-scale energy data.
- Reduce dataset complexity using PCA.
- Identify groups of similar buildings using K-Means Clustering.
- Explore energy consumption patterns.
- Visualize relationships within the dataset.
- Generate insights for energy-efficient building management.

---

# 🛠 Tech Stack

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn (Machine Learning)
- PCA (Principal Component Analysis)
- K-Means Clustering

---

# 📚 Machine Learning Concepts Used

## 🔹 Principal Component Analysis (PCA)

Principal Component Analysis (PCA) is a dimensionality reduction technique.

Large datasets often contain many features, making visualization and analysis difficult. PCA transforms the original features into a smaller set of new variables called **Principal Components**, while preserving most of the important information.

### Why PCA?

- Reduces dimensionality
- Removes redundant information
- Speeds up machine learning algorithms
- Helps visualize high-dimensional data in 2D or 3D

Example:

Instead of analyzing 20 different building features separately, PCA can summarize them into just 2 or 3 principal components while retaining most of the dataset's variance.

---

## 🔹 K-Means Clustering

K-Means is an **unsupervised machine learning algorithm** used to group similar data points.

It divides the dataset into **K clusters**, where each cluster contains buildings with similar characteristics.

### How K-Means Works

1. Choose the number of clusters (K).
2. Randomly initialize cluster centers.
3. Assign each data point to its nearest cluster.
4. Update cluster centers.
5. Repeat until the clusters no longer change significantly.

### Why K-Means?

- Finds hidden patterns in data
- Groups similar buildings together
- Helps identify high-energy and low-energy consumption clusters
- Useful for segmentation and exploratory data analysis

---

# 📈 Project Workflow

1. Data Loading
2. Data Cleaning
3. Feature Selection
4. Data Standardization
5. Principal Component Analysis (PCA)
6. K-Means Clustering
7. Cluster Visualization
8. Result Interpretation

---

# 📊 Analysis Performed

- Data preprocessing
- Feature scaling
- PCA transformation
- Cluster formation using K-Means
- Visualization of clusters
- Building energy pattern analysis

---

# ▶️ Getting Started

## Clone Repository

```bash
git clone https://github.com/Mehak1314/Smart-Building-Energy-Analysis.git
cd Smart-Building-Energy-Analysis
```

## Install Dependencies

```bash
pip install pandas numpy matplotlib scikit-learn
```

## Run the Notebook

Open:

```
ai_project.ipynb
```

Run all cells to reproduce the complete analysis.

---

# 📂 Repository Structure

```
Smart-Building-Energy-Analysis/
│
├── ai_project.ipynb
├── README.md
```

---

# 🚀 Future Improvements

- Hierarchical Clustering
- DBSCAN Clustering
- Energy Consumption Forecasting
- Interactive Dashboard using Power BI or Tableau
- Real-time IoT Data Integration
- Anomaly Detection for Energy Monitoring

---

# 📜 License

This project is intended for educational and academic purposes.

---

# 👩‍💻 Author

**Mehak Garg**

GitHub: https://github.com/Mehak1314

---

⭐ If you found this project useful, consider giving it a star!
