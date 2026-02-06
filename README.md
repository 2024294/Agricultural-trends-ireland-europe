# Agricultural Trends and Insights: A Comparative Analysis of Ireland and European Countries

This project presents a comprehensive analysis of agricultural trends in **Ireland**
and selected European countries (**Germany, France, and the Netherlands**),
focusing on **production, harvested area, yield, and trade performance**.

The study combines **data preparation, statistical analysis, machine learning,
clustering, and sentiment analysis** to evaluate Ireland’s agricultural position
and identify strengths, limitations, and opportunities for sustainable growth.

---

## 📊 Data Sources
- **FAOSTAT (Food and Agriculture Organization of the United Nations)**
- Time period: **1961–2022**
- Datasets include:
  - Crop production
  - Area harvested
  - Yield
  - Export & import quantities
  - Export & import values

Data is licensed under **Creative Commons Attribution 4.0 (CC BY 4.0)**.

---

## 🛠️ Technologies & Tools
- **Python**
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- SciPy
- NLTK
- Jupyter Notebook

---

## 🔄 Methodology
The project follows the **SEMMA framework**:
- **Sample:** FAOSTAT agricultural datasets
- **Explore:** Exploratory Data Analysis (EDA) with visualizations
- **Modify:** Data cleaning, imputation, outlier treatment (IQR)
- **Model:** Statistical tests, regression, clustering, sentiment analysis
- **Assess:** Model comparison and evaluation

---

## 🧹 Data Preparation
- Removal of redundant features
- Dataset merging and restructuring using pivot tables
- Missing value handling using mean/median imputation
- Outlier detection and treatment using the **Interquartile Range (IQR)**
- Feature engineering:
  - Yield
  - Trade balance
  - Trade ratio
  - Export & import prices
- Data scaling:
  - Min–Max Scaling
  - Z-score normalization

---

## 📐 Statistical Analysis
- Descriptive statistics
- Distribution analysis (skewness, kurtosis, KDE)
- Confidence intervals (95%)
- Hypothesis testing:
  - Mann–Whitney U Test
  - Spearman Correlation
  - Independent T-Test
  - Z-Test
  - One-Way ANOVA
  - Kruskal–Wallis Test

---

## 🤖 Machine Learning

### Regression Models (Prediction)
Goal: Predict **export quantities** based on production and trade variables.

Models compared:
- Multiple Linear Regression
- Polynomial Regression
- K-Nearest Neighbors (KNN)
- Support Vector Regression (SVR)

**Best performing models:**
- Polynomial Regression (GridSearchCV)
- KNN Regression (K-Fold Cross Validation)

---

### Clustering
- **K-Means Clustering** with **PCA**
- Optimal clusters selected using:
  - Elbow Method
  - Silhouette Score
- Countries and crops grouped based on production and trade similarity

---

## 💬 Sentiment Analysis
- Reddit data related to **Ireland and agriculture**
- Text preprocessing:
  - Tokenization
  - Stop-word removal
  - Stemming & lemmatization
- Models:
  - **VADER**
  - **Bag of Words**
- Visualization:
  - WordClouds
  - Frequency distributions

---

## 📈 Key Findings
- Ireland shows strong yield performance in selected crops but lower total production
- Trade balance indicates limited competitiveness in some commodity markets
- Polynomial and KNN regression models achieved high predictive accuracy
- Clustering revealed distinct agricultural and trade profiles across countries
- Public sentiment toward Irish agriculture is mixed, with economic and political themes prominent

---

## 🎓 Context
Originally developed as part of an **MSc in Data Analytics**.
This repository contains a **cleaned and refactored version**
prepared for professional portfolio presentation.

---

## 👤 Author
**Mesut UGUR**  
MSc Data Analytics  
