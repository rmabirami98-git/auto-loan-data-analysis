# auto-loan-data-analysis

This repository contains a collection of Jupyter notebooks for **data preprocessing, analysis, quality checking, segmentation, and predictive modeling for Auto Loan Data**.  
It is designed as a modular pipeline where each notebook addresses a specific step in the data science workflow.  

---

## 📁 Project Structure

- **`DataPreprocessor.ipynb`**  
  Handles data cleaning, feature transformations, missing value imputation, and encoding.  

- **`DataQualityChecker.ipynb`**  
  Evaluates data quality with checks for missing data, duplicates, data types, and inconsistencies.
  
- **`DataAnalyser.ipynb`**  
  Provides exploratory data analysis (EDA), summary statistics, and visual insights into the dataset.  

- **`PerformanceSegmentation.ipynb`**  
  Performs segmentation analysis to identify performance groups, clusters, or cohorts within the dataset.  

- **`PredictiveModelling.ipynb`**  
  Builds and evaluates machine learning models for predictive tasks.  

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/rmabirami98-git/auto-loan-data-analysis.git
cd auto-loan-data-analysis/python-notebooks
````

### 2. Install dependencies

We recommend creating a virtual environment and installing required libraries:

```bash
pip install -r requirements.txt
```

### 3. Run the notebooks

You can open any notebook with Jupyter:

```bash
jupyter notebook
```

---

## 📌 Requirements

* Python 3.13.7
* Jupyter Notebook
* pandas, numpy, matplotlib, seaborn, scikit-learn
---

## 📊 Example Workflow

1. Preprocess your dataset using `DataPreprocessor.ipynb`.
2. Validate its quality with `DataQualityChecker.ipynb`.
3. Explore and visualize it with `DataAnalyser.ipynb`.
4. Segment the data using `PerformanceSegmentation.ipynb`.
5. Build Logistic models for approval and funding with `PredictiveModelling.ipynb`.

