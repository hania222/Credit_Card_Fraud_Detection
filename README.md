# 🛡️ Credit Card Fraud Detection – Data Analysis Project

This project focuses on **exploratory data analysis (EDA)** and **preprocessing** of a credit card transaction dataset to identify potential patterns in fraudulent activities. The visual insights are presented through an interactive **Power BI dashboard**.

## 📦 Dataset

The dataset contains credit card transactions with labeled classes:
- **0** = Legitimate
- **1** = Fraudulent

It includes anonymized numerical features (V1–V28), `Amount`, `Time`, and a binary `Class` label.

> 📁 Dataset available in 'https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud'

## 🔧 Tools Used

- 🐍 Python (Google Colab)
- 📊 Power BI (Data Visualization)
- 📁 Pandas, NumPy, Seaborn, Matplotlib (for EDA)


## 📋 Key Steps

### ✅ Data Preprocessing in Colab

- Loaded dataset and checked structure
- Handled missing values and duplicates (if any)
- Checked and Remove outliers
- Renamed columns for clarity 
- Converted time into `Hour` feature for time-based analysis
- Created categorical bins for `Amount` to group transaction sizes

📍 [View Colab Notebook](https://colab.research.google.com/drive/1Y0lvS-jk1YtXSvKhNSQ2dwf7YtkLg55Z?usp=sharing)


---

## 📊 Power BI Dashboard

The report highlights the following:

- **Total Transactions** 
- **Transaction Amount Distribution** (Legit vs Fraud)
- **Fraud Occurrence by Hour**
- **Fraud Count by Amount Category** (Small, Medium, Large, Very Large)

> 📁 Power BI file: `project2(PowerBI).pbix`

---

## 📁 Folder Structure

