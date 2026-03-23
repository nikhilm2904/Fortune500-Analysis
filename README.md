# Fortune 500 — Revenue Stability Analysis (2020–2023)

**Course:** Analytical Methods in Engineering Systems  
**Authors:** Mahesh Kanchipal & Nikhil M  
**Submission Date:** March 15, 2026

---

## 📌 Project Overview

This project analyzes the **revenue stability and financial performance** of Fortune 500 companies over a 4-year period (2020–2023). Using a dataset of 500 companies across multiple sectors, we apply a comprehensive set of analytical methods — from descriptive statistics to PCA — to uncover patterns, trends, and risks in corporate financial data.

---

## 📂 Repository Structure
```
Fortune500-Analysis/
├── Revenue_Stability_Over_Time_Mahesh_Kanchipal_Nikhil_M.ipynb   # Main analysis notebook
├── Fortuene500-Company-100-Dataset.csv                            # Dataset
├── Revenue_Stability_Over_Time_Mahesh_Kanchipal_Nikhil_M.pdf     # PDF export of notebook
└── README.md
```

---

## 📊 Dataset

- **Source:** Kaggle — Fortune 500 Company Dataset
- **File:** `Fortuene500-Company-100-Dataset.csv`
- **Coverage:** 500 Fortune 500 companies × 4 years (2020–2023)
- **Features:** Revenue, Profit, Market Value, Assets, Employees, Sector, CEO Demographics, Global 500 membership, and more
- **Target Variables:** `revenue_mil`, `profit_mil`, `market_value_mil`

---

## 🔍 Analysis Sections

| # | Section | Key Methods |
|---|---------|-------------|
| 1 | Data Understanding | Data types, observations, variables, tabular preview |
| 2 | Descriptive Statistics | Mean, Median, Variance, IQR, Five-number summary, Outlier detection |
| 3 | Visualizations | Histogram, Boxplot, Bar, Scatter, Line, Grouped/Stacked Bar, Heatmaps, Scree Plot, PCA Plot |
| 4 | Probability Analysis | Basic probability, Conditional probability, Bayes' Theorem, Normal distribution |
| 5 | Inferential Statistics | Confidence intervals, T-test, Chi-square, One-way ANOVA, Two-way ANOVA |
| 6 | Linear Algebra | Matrix form, Mean-centering, Covariance/Correlation matrices, Eigendecomposition, PCA |
| 7 | Insight Generation | Patterns, Anomalies, Risk flags, Sector consistency, Limitations |
| 8 | Conclusions | Industry-relevant findings with statistical evidence |

---

## 🚀 How to Run

1. Clone this repository:
```bash
   git clone https://github.com/<your-username>/Fortune500-Analysis.git
   cd Fortune500-Analysis
```

2. Install required libraries:
```bash
   pip install pandas numpy matplotlib seaborn scipy scikit-learn statsmodels
```

3. Open the notebook:
```bash
   jupyter notebook Revenue_Stability_Over_Time_Mahesh_Kanchipal_Nikhil_M.ipynb
```

4. Make sure `Fortuene500-Company-100-Dataset.csv` is in the **same directory** as the notebook before running.

---

## 📦 Requirements

| Library | Purpose |
|---|---|
| `pandas` | Data manipulation |
| `numpy` | Numerical computation |
| `matplotlib` | Plotting |
| `seaborn` | Statistical visualizations |
| `scipy` | Statistical tests |
| `scikit-learn` | PCA, StandardScaler |
| `statsmodels` | Two-way ANOVA |

---

## 📈 Key Findings

1. Revenue and profit are **right-skewed** — dominated by mega-companies like Walmart, Amazon, Apple
2. **Technology sector** has the highest average market value despite not leading in revenue
3. Revenue **grew significantly** from 2020 to 2023 (t-test p < 0.05)
4. Profit varies **significantly across sectors** (one-way ANOVA p < 0.001)
5. Technology companies have a **~67% probability** of being in Global 500 (Bayes analysis)
6. **Female CEO presence is ~8%** with no significant association to Global 500 membership
7. **Energy sector** shows high revenue but moderate profit margins due to commodity volatility
8. Several companies show **consistent losses** — risk flags for investors

---

## ⚠️ Limitations

- Survivorship bias — only Fortune 500 companies included
- Short 4-year window covering COVID-19 recovery period
- Findings apply only to large-cap U.S. companies
- Derived columns may propagate base data errors
- Missing values for some companies in certain years

---

## 📄 License

This project is submitted for academic purposes only as part of the Analytical Methods in Engineering Systems course.
```

After pasting, scroll down → commit message: `Add README` → click **"Commit changes"**

---

## Step 3 — Upload Your 3 Files

1. In the repo, click **"Add file" → "Upload files"**
2. Drag and drop all 3 files:
   - `Revenue_Stability_Over_Time_Mahesh_Kanchipal_Nikhil_M.ipynb`
   - `Fortuene500-Company-100-Dataset.csv`
   - `Revenue_Stability_Over_Time_Mahesh_Kanchipal_Nikhil_M.pdf`
3. Commit message: `Add project files — notebook, dataset and PDF export`
4. Click **"Commit changes"**

---

## Step 4 — Final Check

Once done, your repo at `github.com/<your-username>/Fortune500-Analysis` should look like this:
```
Fortune500-Analysis/
├── 📓 Revenue_Stability_Over_Time_Mahesh_Kanchipal_Nikhil_M.ipynb
├── 📊 Fortuene500-Company-100-Dataset.csv
├── 📄 Revenue_Stability_Over_Time_Mahesh_Kanchipal_Nikhil_M.pdf
└── 📝 README.md
