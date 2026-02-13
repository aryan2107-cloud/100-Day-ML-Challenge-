# 100 Days of Machine Learning Challenge

A hands-on journey from data foundations to production-ready ML systems.

[![Made with Python](https://img.shields.io/badge/Made%20with-Python-blue.svg)](https://www.python.org/)
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![Google Colab](https://img.shields.io/badge/Open%20in-Colab-yellow.svg)](https://colab.research.google.com/)
[![Progress](https://img.shields.io/badge/Progress-17%2F100-brightgreen.svg)](#progress)

---

## About

This repository documents my 100-day challenge to master machine learning through daily projects. Each day produces **working code**, not just theory.

| | |
|---|---|
| **Start Date** | January 2025 |
| **Tools** | Python, Pandas, NumPy, Scikit-learn, Statsmodels |
| **Environment** | Google Colab |
| **Focus** | Understand *why* techniques work, not just *how* |

---

## The Roadmap

| Phase | Days | Focus | Status |
|-------|------|-------|--------|
| **1. Data Foundations** | 1-15 | Data quality, preprocessing, EDA, pipelines | ✅ Complete |
| **2. Classical ML** | 16-40 | Regression, classification, clustering, ensembles | 🔄 In Progress |
| **3. Deep Learning** | 41-65 | Neural networks, CNNs, RNNs | 🔲 Coming Soon |
| **4. Specialized Topics** | 66-85 | NLP, time series, recommenders | 🔲 Coming Soon |
| **5. Production & Projects** | 86-100 | Deployment, end-to-end projects | 🔲 Coming Soon |

---

## Progress

### Phase 1: Data Foundations (Days 1-15) — COMPLETE

| Day | Topic | Dataset | Key Concepts |
|-----|-------|---------|--------------|
| 01 | [Synthetic Data Generator](Day01(SyntheticData).ipynb) | Custom | NumPy, data generation, noise injection |
| 02 | [Missing Data Forensics](Day02(DataForensics).ipynb) | Custom | MCAR/MAR/MNAR, imputation strategies |
| 03 | [Distribution Detective](Day03(DataDistribution).ipynb) | Titanic | Skewness, kurtosis, transformations |
| 04 | [Feature Engineering Pipeline](Day04_Feature_Engineering_Pipeline.ipynb) | Titanic | Encoding, scaling, feature creation |
| 05 | [Outlier Detection](Day05_Outlier_detection.ipynb) | NYC Taxi | Z-score, IQR, Isolation Forest, LOF |
| 06 | [EDA Toolkit](Day06(EDA).ipynb) | Heart Disease | Univariate, bivariate, correlation analysis |
| 07 | [Cross-Validation Deep Dive](Day07_Cross_Validation.ipynb) | Heart Disease | K-Fold, Stratified, Time Series, Nested CV |
| 08 | Data Leakage Detection | Credit Card Fraud | Train-test contamination, temporal leakage |
| 09 | [Imbalanced Data Strategies](Day09_Imbalanced_Data.ipynb) | Telecom Churn | SMOTE, undersampling, class weights |
| 10 | [Feature Selection Methods](Day10_Feature_Selection.ipynb) | Ames Housing | Filter, wrapper, embedded methods |
| 11 | [Dimensionality Reduction](Day11_Dimensionality_Reduction.ipynb) | MNIST | PCA, t-SNE, UMAP |
| 12 | [Data Pipelines](Day12_Data_Pipelines.ipynb) | Adult Income | Pipeline, ColumnTransformer, custom transformers |
| 13 | [Time Series Basics](Day13_Time_Series_Basics.ipynb) | Air Passengers | Trends, seasonality, stationarity, ACF/PACF |
| 14 | [Text Preprocessing](Day14_Text_Preprocessing.ipynb) | SMS Spam | Tokenization, TF-IDF, NLP pipeline |
| 15 | [Phase 1 Capstone](Day15_Capstone_Rain_Prediction.ipynb) | Australia Weather | End-to-end ML project using all Phase 1 skills |

---

### Phase 2: Classical Machine Learning (Days 16-40) — IN PROGRESS

| Day | Topic | Dataset | Key Concepts |
|-----|-------|---------|--------------|
| 16 | [Linear Regression Deep Dive](Day16_Linear_Regression.ipynb) | Auto MPG | OLS, assumptions, diagnostics, VIF, multicollinearity |
| 17 | [Polynomial & Regularization](Day17_Polynomial_Regularization.ipynb) | Bike Sharing | Polynomial features, Ridge, Lasso, Elastic Net |
| 18 | Logistic Regression | TBD | Classification, odds ratios, decision boundary |
| 19-20 | Decision Trees | TBD | Splitting criteria, pruning, visualization |
| 21-25 | Ensemble Methods | TBD | Random Forest, Gradient Boosting, XGBoost |
| 26-30 | SVM & KNN | TBD | Kernels, distance metrics, hyperparameter tuning |
| 31-35 | Clustering | TBD | K-Means, DBSCAN, Hierarchical |
| 36-40 | Advanced + Capstone | TBD | Model selection, Phase 2 capstone |

---

## Skills Mastered

### Phase 1: Data Foundations ✅
| Category | Skills |
|----------|--------|
| **Data Quality** | Missing data handling, outlier detection, data validation |
| **Preprocessing** | Scaling, encoding, transformations, pipelines |
| **EDA** | Distributions, correlations, visualization |
| **Feature Engineering** | Creation, selection, dimensionality reduction |
| **Model Evaluation** | Cross-validation, leakage prevention, metrics |
| **Special Data Types** | Time series, text data |

### Phase 2: Classical ML 🔄
| Category | Skills |
|----------|--------|
| **Regression** | Linear, polynomial, regularization (Ridge/Lasso/Elastic Net) |
| **Diagnostics** | Assumptions, residuals, VIF, multicollinearity |
| **Coming Soon** | Classification, trees, ensembles, clustering |

---

## Datasets Used

| Dataset | Days | Source | Type |
|---------|------|--------|------|
| Titanic | 3, 4 | Kaggle | Classification |
| NYC Taxi | 5 | NYC TLC | Regression |
| Heart Disease | 6, 7 | UCI | Classification |
| Credit Card Fraud | 8 | Kaggle | Classification |
| Telecom Churn | 9 | IBM | Classification |
| Ames Housing | 10 | OpenML | Regression |
| MNIST | 11 | OpenML | Classification |
| Adult Income | 12 | UCI | Classification |
| Air Passengers | 13 | Classic | Time Series |
| SMS Spam | 14 | UCI | NLP/Classification |
| Australia Weather | 15 | Kaggle | Classification |
| Auto MPG | 16 | UCI | Regression |
| Bike Sharing | 17 | UCI | Regression |

---

## 📈 Key Takeaways by Day

| Day | One-Liner |
|-----|-----------|
| 01 | Generate realistic synthetic data for testing |
| 02 | Missing data has patterns — detect before imputing |
| 03 | Always visualize distributions before modeling |
| 04 | Feature engineering is where domain knowledge shines |
| 05 | Not all outliers are errors — context matters |
| 06 | EDA should be systematic, not random exploration |
| 07 | Use the right CV for your data structure |
| 08 | Data leakage = amazing dev metrics, terrible production |
| 09 | Accuracy is useless on imbalanced data |
| 10 | More features ≠ better model |
| 11 | PCA for preprocessing, t-SNE/UMAP for visualization |
| 12 | Pipelines prevent leakage and enable reproducibility |
| 13 | Never shuffle time series — use temporal splits |
| 14 | TF-IDF beats raw counts for text classification |
| 15 | End-to-end projects require ALL skills together |
| 16 | Check assumptions before trusting linear regression |
| 17 | Regularization prevents overfitting with many features |

---

## 🛠️ How to Use

### Option 1: Google Colab (Recommended)
1. Click on any notebook link in the Progress table
2. Click "Open in Colab" badge at the top of the notebook
3. Run cells sequentially

### Option 2: Local Setup
```bash
# Clone the repo
git clone https://github.com/aryan2107-cloud/100-Day-ML-Challenge-.git
cd 100-Day-ML-Challenge-

# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install numpy pandas matplotlib seaborn scikit-learn statsmodels imbalanced-learn umap-learn nltk
```

---

## 🔜 Coming Up Next

### Phase 2 Continuation (Days 18-40)
- **Day 18:** Logistic Regression
- **Days 19-20:** Decision Trees
- **Days 21-25:** Ensemble Methods (Random Forest, XGBoost, LightGBM)
- **Days 26-30:** SVM & KNN
- **Days 31-35:** Clustering Algorithms
- **Days 36-40:** Advanced Topics + Phase 2 Capstone

### Future Phases
- **Phase 3 (Days 41-65):** Deep Learning — Neural Networks, CNNs, RNNs
- **Phase 4 (Days 66-85):** Specialized Topics — NLP, Time Series, Recommenders
- **Phase 5 (Days 86-100):** Production — Deployment, MLOps, Final Projects

---

## Connect

- **GitHub:** [@aryan2107-cloud](https://github.com/aryan2107-cloud)
- **Questions?** Open an issue!

---

## Support

If you find this helpful, consider giving it a star! It helps others discover the repo.

---

<p align="center">
  <i>"The best way to learn is to build."</i>
</p>

<p align="center">
  <b>Current Progress: Day 17 of 100</b>
</p>

<p align="center">
  <b>Phase 1 Complete | 🔄 Phase 2 In Progress</b>
</p>
