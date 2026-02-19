# customer_segmentation_and_analysis_using_python
A data-driven customer segmentation project using K-Means clustering to uncover valuable customer groups and improve business decision-making.
## 📌 Table of Contents

- 🔎 [Project Overview](#project-overview)
- 🎯 [Business Problem](#business-problem)
- 📂 [Dataset](#dataset)
- 🛠️ [Tools & Technologies](#tools--technologies)
- 📁 [Folder Structure](#folder-structure)
- 🧹 [Data Cleaning & Preparation](#data-cleaning--preparation)
- 📚 [Libraries Used](#libraries-used)
- 📊 [Exploratory Data Analysis (EDA) & Clustering](#exploratory-data-analysis-eda--clustering)
- 💡 [Key Insights & Recommendations](#key-insights--recommendations)
- 🔗 [References](#references)
- 👨‍💻 [Author & Contact](#author--contact)
---
## 🔎 Project Overview

This project performs customer segmentation using K-Means clustering to group customers based on spending behavior and income levels. The analysis includes data cleaning, exploratory data analysis (EDA), and cluster visualization to generate actionable business insights.
The project covers the complete data analysis workflow — including data cleaning, exploratory data analysis (EDA), feature selection, optimal cluster identification using the Elbow Method, and visualization of customer groups. By applying unsupervised machine learning techniques, the analysis reveals meaningful patterns within the dataset and provides actionable business insights.

---

## 🎯 Business Problem

The company lacks a structured way to segment customers based on purchasing behavior. The objective is to use K-Means clustering to identify distinct customer groups that can help improve targeted marketing and increase business revenue.
Businesses often treat all customers the same, using uniform marketing strategies without understanding differences in customer behavior. However, customers vary significantly in terms of purchasing patterns, income levels, and spending habits.

---

<h2 id="dataset">📂 Dataset</h2>

The dataset contains information about mall customers, including the following columns:

- CustomerID – Unique identifier for each customer

- Gender – Male or Female

- Age – Customer’s age in years

- Annual Income (k$) – Yearly income in thousands of dollars

- Spending Score (1–100) – A score representing customer spending behaviour

This dataset serves as the basis for exploratory analysis and K-Means clustering to identify customer segments.

---

<h2 id="tools-and-technologies">🛠️ Tools & Technologies</h2>

- Python – Programming language for data analysis

- Jupyter Notebook – Development environment for interactive coding

- Pandas – Data manipulation and preprocessing

- Matplotlib & Seaborn – Data visualization

- Scikit-learn – K-Means clustering, StandardScaler, One-Hot Encoding

These tools enabled end-to-end analysis, from data exploration to cluster modeling and visualization.

---

Customer-Segmentation-Project/
│
├── data/
│   └── Mall_Customers.csv
│
├── notebooks/
│   └── customer_segmentation.ipynb
│
├── images/
│   ├── elbow_method.png
│   ├── cluster_visualization.png
│   └── pairplot.png
│
├── README.md
└── requirements.txt

---
