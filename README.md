# Exploratory-Data-Analysis-EDA-
Extract insights using visual and statistical exploration using Python (Pandas, Matplotlib, Seaborn)

# Titanic EDA – Kaggle Dataset

##  Project Overview
This repository contains a **comprehensive Exploratory Data Analysis (EDA)** of the Titanic dataset from Kaggle.  
The analysis focuses on understanding survival patterns using descriptive statistics and visualization.

##  Tools & Libraries
- Python
- Pandas
- Matplotlib
- Seaborn (optional, for pairplots/heatmaps)
- Jupyter Notebook

##  EDA Highlights
- Used `.info()`, `.describe()`, `.value_counts()` for structure and summary.
- Checked missing values and provided recommendations for handling.
- **Histograms & Boxplots** for numerical distributions (Age, Fare).
- **Bar charts** for categorical variables (Sex, Pclass, Embarked).
- **Survival analysis** by Sex, Pclass, and Embarked with clear differences observed.
- **Scatterplots** to analyze Age vs Fare with survival outcome.
- **Correlation heatmap** for numeric features.
- Observations are written for each visual to interpret findings.
- A professional PDF report is included.

##  Files
- `Exploratory Data Analysis.ipynb` – Jupyter Notebook with step-by-step EDA.
- `Titanic_EDA_Final_Report.pdf` – Multi-page PDF report with visuals + observations.
- `train.csv`, `test.csv`, `gender_submission.csv` – Dataset files.

## 🚀 How to Run
1. Clone this repository
2. Install dependencies:
   ```bash
   pip install pandas matplotlib seaborn jupyter
   ```
3. Launch Jupyter Notebook:
   ```bash
   Jupyter Notebook "Exploratory Data Analysis.ipynb"
   ```
4. Run the cells sequentially to reproduce the EDA.

##  Key Findings
- Women and 1st class passengers had higher survival rates.
- Fare correlates positively with survival (proxy for class).
- Age distribution shows children had better outcomes.
- Cabin feature is mostly missing – can be engineered as `HasCabin`.
- Family size has a non-linear effect on survival.

##  Next Steps
- Feature engineering (`FamilySize`, `IsAlone`, `Title` from names).
- Handle missing values appropriately (Age imputation, Cabin flag, Embarked mode).
- Baseline modeling with Logistic Regression / Decision Trees for predictive insights.

---
## Author
Kadimella Sahana
