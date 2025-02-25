# Credit Data Exploratory Data Analysis (EDA)

This repository contains a Jupyter Notebook that performs an in-depth exploratory data analysis (EDA) on credit data. The analysis focuses on understanding customer demographics, credit behavior, and patterns that can help in risk assessment and decision-making.

---

## 📋 **Project Overview**
The goal of this project is to analyze credit-related data to uncover insights and trends that can guide financial institutions in assessing credit risk. The notebook includes:
- Data cleaning and preprocessing.
- Statistical analysis of key features.
- Visualization of trends and correlations.
- Insights into customer behavior and credit performance.

---

## 🛠️ **Features**
- **Data Cleaning**: Handling missing values, outliers, and inconsistent data.
- **Exploratory Analysis**:
  - Distribution of income, credit amount, and annuities.
  - Correlation analysis between variables like income, age, and credit risk.
  - Analysis of categorical variables such as contract type, education level, and family status.
- **Visualization**:
  - Histograms, box plots, and scatter plots for numerical features.
  - Heatmaps for correlation matrices.
  - Bar charts for categorical features.

---

## 📂 **Files in the Repository**
1. **`EDA-CREDIT.ipynb`**: Jupyter Notebook containing the complete EDA workflow.
2. **Data Files**: Due to size limitations, the dataset is not included in this repository. See the instructions below on how to obtain or prepare the data.

---

## 📊 **Dataset Information**
The dataset used in this project contains information about customers' demographics, financial status, and credit history. Key columns include:
- `SK_ID_CURR`: Unique customer ID.
- `AMT_INCOME_TOTAL`: Total income of the customer.
- `AMT_CREDIT`: Total credit amount applied for.
- `TARGET`: Binary indicator (1 = defaulted loan, 0 = non-defaulted loan).
- `NAME_CONTRACT_TYPE`, `CODE_GENDER`, `NAME_EDUCATION_TYPE`, etc.

---

## 🚀 **How to Use**
1. Clone this repository: https://github.com/shadab007-byte/CREDIT_EDA

2. Download the dataset:
- If you have access to the dataset (`application_data.csv`), place it in the same directory as the notebook.
- Alternatively, you can download a similar dataset from [Kaggle](https://www.kaggle.com/) or other open data sources related to credit scoring or loan applications.

3. Follow the steps in the notebook to reproduce the analysis.

---

## 🔗 **Sample Dataset Sources**
If you do not have access to the original dataset used in this project, consider downloading similar datasets from these sources:
- [Kaggle Credit Default Dataset](https://www.kaggle.com/)
- Public financial datasets from [UCI Machine Learning Repository](http://archive.ics.uci.edu/ml/index.php)

---

## 🧰 **Dependencies**
This project uses Python libraries for data manipulation and visualization:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`

Ensure you have Python 3.x installed along with these libraries.

---

## 📜 **License**
This project is licensed under the MIT License. Feel free to use or modify it as needed.

---

## 🤝 **Contributing**
Contributions are welcome! If you have suggestions or improvements, please create a pull request or open an issue.

---

## ✨ **Acknowledgments**
Special thanks to open data platforms like Kaggle for providing access to high-quality datasets that make projects like this possible.



