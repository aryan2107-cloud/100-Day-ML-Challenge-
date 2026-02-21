# 100 Days of Machine Learning

My hands-on journey through machine learning, from data basics to production-ready models.

**Progress:** 25/100 days

---

## What's This About?

I'm working through 100 days of ML projects, focusing on actually building things rather than just reading theory. Each day produces working code in Jupyter notebooks.

**Tools:** Python, Pandas, NumPy, Scikit-learn, XGBoost, LightGBM  
**Environment:** Google Colab

---

## Roadmap

| Phase | Days | Focus | Status |
|-------|------|-------|--------|
| 1. Data Foundations | 1-15 | Data quality, preprocessing, pipelines | ✅ Done |
| 2. Classical ML | 16-40 | Regression, classification, clustering | In Progress |
| 3. Deep Learning | 41-65 | Neural networks, CNNs, RNNs | Coming Soon |
| 4. Specialized Topics | 66-85 | NLP, time series, recommenders | Coming Soon |
| 5. Production | 86-100 | Deployment, end-to-end projects | Coming Soon |

---

## Phase 1: Data Foundations (Complete)

| Day | Topic | Dataset | What I Learned |
|-----|-------|---------|----------------|
| 01 | Synthetic Data | Custom | Generating realistic test data |
| 02 | Missing Data | Custom | MCAR/MAR/MNAR, imputation strategies |
| 03 | Distributions | Titanic | Skewness, transformations |
| 04 | Feature Engineering | Titanic | Encoding, scaling, creating features |
| 05 | Outlier Detection | NYC Taxi | Z-score, IQR, Isolation Forest |
| 06 | EDA | Heart Disease | Systematic exploration approach |
| 07 | Cross-Validation | Heart Disease | K-Fold, Stratified, Nested CV |
| 08 | Data Leakage | Credit Card Fraud | How to accidentally cheat |
| 09 | Imbalanced Data | Telecom Churn | SMOTE, class weights |
| 10 | Feature Selection | Ames Housing | Filter, wrapper, embedded methods |
| 11 | Dimensionality Reduction | MNIST | PCA, t-SNE, UMAP |
| 12 | Pipelines | Adult Income | Reproducible preprocessing |
| 13 | Time Series Basics | Air Passengers | Trends, seasonality, stationarity |
| 14 | Text Preprocessing | SMS Spam | Tokenization, TF-IDF |
| 15 | **Capstone** | Australia Weather | Everything together |

---

## Phase 2: Classical ML (In Progress)

### Regression

| Day | Topic | Dataset | Key Takeaway |
|-----|-------|---------|--------------|
| 16 | Linear Regression | Auto MPG | Assumptions matter — check VIF, residuals |
| 17 | Regularization | Bike Sharing | Ridge vs Lasso vs Elastic Net |

### Classification

| Day | Topic | Dataset | Key Takeaway |
|-----|-------|---------|--------------|
| 18 | Logistic Regression | Diabetes | Odds ratios, threshold tuning |
| 19 | Decision Trees | Mushroom | Interpretable but prone to overfitting |
| 20 | Random Forest | Covertype | Bagging reduces variance |
| 21 | Gradient Boosting | California Housing | XGBoost, LightGBM, early stopping |
| 22 | SVM | Breast Cancer | Kernels, the margin concept |
| 24 | KNN | Iris | Simple but watch out for high dimensions |
| 25 | Naive Bayes | SMS Spam | Fast, works surprisingly well for text |

### Coming Up

- Day 26: K-Means Clustering
- Days 27-30: More clustering (DBSCAN, Hierarchical)
- Days 31-35: Model selection, ensembles
- Days 36-40: Phase 2 capstone

---

## Key Lessons So Far

**Data (Phase 1):**
- Missing data has patterns — figure them out before imputing
- Data leakage will give you amazing metrics and a useless model
- Pipelines aren't optional, they're essential

**Models (Phase 2):**
- Start simple. Linear/logistic regression are hard to beat sometimes
- Random Forest is a solid default for most tabular data
- Gradient boosting usually wins competitions, but tune carefully
- Always scale features for SVM and KNN

---

## How to Use These Notebooks

**Option 1: Colab (easiest)**
1. Click any notebook
2. Open in Colab
3. Run cells

**Option 2: Local**
```bash
git clone https://github.com/yourusername/100-days-of-ml.git
cd 100-days-of-ml
pip install -r requirements.txt
```

---

## Datasets Used

| Dataset | Source | Days |
|---------|--------|------|
| Titanic | Kaggle | 3, 4 |
| Heart Disease | UCI | 6, 7 |
| MNIST | OpenML | 11 |
| SMS Spam | UCI | 14, 25 |
| Australia Weather | Kaggle | 15 |
| Auto MPG | UCI | 16 |
| Bike Sharing | UCI | 17 |
| Diabetes | UCI | 18 |
| Mushroom | UCI | 19 |
| Covertype | sklearn | 20 |
| California Housing | sklearn | 21 |
| Breast Cancer | sklearn | 22 |
| Iris | sklearn | 24 |

---

## What's Next

Currently on Day 26 (K-Means Clustering). Phase 2 should wrap up around Day 40, then it's on to neural networks.

---

## Connect

GitHub: [@aryan2107-cloud](https://github.com/aryan2107-cloud)

Found something useful? Star the repo.
