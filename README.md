# 100 Days of Machine Learning Challenge

A hands-on journey from data foundations to production-ready ML systems.

[![Made with Python](https://img.shields.io/badge/Made%20with-Python-blue.svg)](https://www.python.org/)
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![Google Colab](https://img.shields.io/badge/Open%20in-Colab-yellow.svg)](https://colab.research.google.com/)
[![Progress](https://img.shields.io/badge/Progress-12%2F100-brightgreen.svg)](#progress)

---

## About

This repository documents my 100-day challenge to master machine learning through daily projects. Each day produces **working code**, not just theory.

| | |
|---|---|
| **Start Date** | January 2025 |
| **Tools** | Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn |
| **Environment** | Google Colab |
| **Focus** | Understand *why* techniques work, not just *how* |

---

## The Roadmap

| Phase | Days | Focus | Status |
|-------|------|-------|--------|
| **1. Data Foundations** | 1-15 | Data quality, preprocessing, EDA, pipelines | 🔄 In Progress |
| **2. Classical ML** | 16-40 | Regression, classification, clustering, ensembles | 🔲 Coming Soon |
| **3. Deep Learning** | 41-65 | Neural networks, CNNs, RNNs | 🔲 Coming Soon |
| **4. Specialized Topics** | 66-85 | NLP, time series, recommenders | 🔲 Coming Soon |
| **5. Production & Projects** | 86-100 | Deployment, end-to-end projects | 🔲 Coming Soon |

---

## Progress

### Phase 1: Data Foundations (Days 1-15)

| Day | Topic | Dataset | Key Concepts | Status |
|-----|-------|---------|--------------|--------|
| 01 | [Synthetic Data Generator](Day01(SyntheticData).ipynb) | Custom | NumPy, data generation, noise injection | ✅ |
| 02 | [Missing Data Forensics](Day02(DataForensics).ipynb) | Custom | MCAR/MAR/MNAR, imputation strategies | ✅ |
| 03 | [Distribution Detective](Day03(DataDistribution).ipynb) | Titanic | Skewness, kurtosis, transformations | ✅ |
| 04 | [Feature Engineering Pipeline](Day04_Feature_Engineering_Pipeline.ipynb) | Titanic | Encoding, scaling, feature creation | ✅ |
| 05 | [Outlier Detection](Day05_Outlier_detection.ipynb) | NYC Taxi | Z-score, IQR, Isolation Forest, LOF | ✅ |
| 06 | [EDA Toolkit](Day06(EDA).ipynb) | Heart Disease | Univariate, bivariate, correlation analysis | ✅ |
| 07 | [Cross-Validation Deep Dive](Day07_Cross_Validation.ipynb) | Heart Disease + Stock | K-Fold, Stratified, Time Series, Nested CV | ✅ |
| 08 | Data Leakage Detection | Credit Card Fraud | Train-test contamination, temporal leakage | ✅ |
| 09 | [Imbalanced Data Strategies](Day09_Imbalanced_Data.ipynb) | Telecom Churn | SMOTE, undersampling, class weights | ✅ |
| 10 | [Feature Selection Methods](Day10_Feature_Selection.ipynb) | Ames Housing | Filter, wrapper, embedded methods | ✅ |
| 11 | [Dimensionality Reduction](Day11_Dimensionality_Reduction.ipynb) | MNIST | PCA, t-SNE, UMAP | ✅ |
| 12 | [Data Pipelines](Day12_Data_Pipelines.ipynb) | Adult Income | Pipeline, ColumnTransformer, custom transformers | ✅ ||

---


---

## 📁 Datasets Used

| Dataset | Days Used | Source |
|---------|-----------|--------|
| Titanic | 3, 4 | Kaggle |
| NYC Taxi | 5 | NYC TLC |
| Heart Disease | 6, 7 | UCI ML Repository |
| Credit Card Fraud | 8 | Kaggle |
| Telecom Churn | 9 | IBM |
| Ames Housing | 10 | OpenML |
| MNIST | 11 | OpenML |
| Adult Income | 12 | UCI ML Repository |

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
pip install numpy pandas matplotlib seaborn scikit-learn imbalanced-learn umap-learn
```

### Option 3: Run Individual Notebooks
Each notebook is self-contained and includes:
- Data loading (from URLs, no local files needed)
- All necessary imports
- Step-by-step explanations
- Visualizations

---

## Key Takeaways by Day

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
  <b>Current Progress: Day 12 of 100</b>
</p>
Following along or have questions? Feel free to open an issue or reach out!

---

*"The best way to learn is to build."*
