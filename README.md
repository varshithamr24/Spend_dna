# 💳 SpendDNA — Transaction Analytics & Spending Behaviour Analysis

**SpendDNA** is a Python-based transaction analytics project that transforms raw transaction data into meaningful insights about spending behaviour.

The project analyses transaction history to understand **spending categories, vendors, monthly trends, time-of-day patterns, unusual transactions, and spending archetypes**.

---

## 📌 Project Overview

Managing transaction data can be difficult when the data contains inconsistent dates, amounts, merchant names, duplicate transactions, and different transaction descriptions.

**SpendDNA** addresses these challenges through an end-to-end Python data analytics workflow.

The project focuses on:

* 🧹 Data cleaning and preprocessing
* 🏪 Merchant/vendor normalization
* 🏷️ Transaction categorization
* 📊 Spending analysis
* 📅 Monthly spending trends
* ⏰ Time-of-day spending patterns
* 🚨 Anomaly detection
* 🧠 Spending behaviour classification
* 📄 Automated SpendDNA report generation

---

## 🎯 Objectives

The main objectives of this project are to:

1. Clean and standardize transaction data.
2. Remove duplicate transactions.
3. Extract and normalize merchant/vendor names.
4. Categorize transactions into meaningful spending categories.
5. Analyse spending patterns over time.
6. Identify unusual or potentially anomalous transactions.
7. Classify spending behaviour into different archetypes.
8. Generate a consolidated spending analysis report.

---

## 🛠️ Technologies Used

| Technology          | Purpose                    |
| ------------------- | -------------------------- |
| 🐍 Python           | Core programming language  |
| 🐼 Pandas           | Data cleaning and analysis |
| 🔢 NumPy            | Numerical operations       |
| 📓 Jupyter Notebook | Development and analysis   |
| 📊 Data Analysis    | Spending pattern analysis  |
| 🚨 Z-Score          | Anomaly detection          |

---

## 📂 Repository Structure

```text
SpendDNA/
│
├── SpendDNA.ipynb
├── DADS MP2 Dataset.csv
├── README.md
├── requirements.txt
└── .gitignore
```

---

## 🔄 Project Workflow

```text
Raw Transaction Data
        ↓
Data Cleaning & Preprocessing
        ↓
Duplicate Removal
        ↓
Vendor Normalization
        ↓
Transaction Categorization
        ↓
Spending Analysis
        ↓
Monthly Trend Analysis
        ↓
Time-of-Day Analysis
        ↓
Anomaly Detection
        ↓
Spending Archetypes
        ↓
SpendDNA Report
```

---

## 🔍 Key Analysis Performed

### 1. Data Cleaning

The transaction dataset is processed to:

* Standardize transaction dates
* Standardize transaction amounts
* Normalize transaction types
* Handle missing/inconsistent values
* Remove duplicate transactions

The notebook reports **1,310 transactions after duplicate removal**.

---

### 2. Vendor Normalization

Transaction descriptions are converted into standardized vendor names.

Examples include:

* Amazon
* Flipkart
* Swiggy
* Zerodha

This makes vendor-level analysis more reliable even when transaction descriptions vary.

---

### 3. Transaction Categorization

Transactions are assigned to spending categories such as:

* E-commerce
* Food Delivery
* Restaurants
* Investments
* Rent
* Quick Commerce
* Other categories

This allows spending behaviour to be analysed at category level.

---

### 4. Spending Overview

SpendDNA calculates key financial metrics including:

* Total credits
* Total debits
* Net savings
* Savings rate
* Transaction count
* Top spending categories
* Top vendors

---

### 5. Monthly Spending Trends

The project analyses spending month-by-month to identify:

* Increasing spending categories
* Decreasing spending categories
* Monthly spending patterns
* Category-level changes

---

### 6. Time-of-Day Analysis

Transactions are analysed according to the hour of the day.

This helps identify when spending activity is highest for different categories.

---

### 7. 🚨 Anomaly Detection

SpendDNA uses a **category-level z-score approach** to identify unusually large transactions.

The current notebook identifies:

**33 anomalous transactions**

These transactions can be investigated further to understand unusual spending behaviour.

---

### 8. 🧠 Spending Archetypes

The project uses rule-based logic to classify spending behaviour.

The current analysis identifies archetypes including:

* 🛍️ **The Shopaholic**
* 🎉 **The YOLO Spender**

These archetypes provide a simple behavioural interpretation of transaction patterns.

---

## 📊 Key Results

Based on the current notebook output:

| Metric                               |         Result |
| ------------------------------------ | -------------: |
| Transactions after duplicate removal |      **1,310** |
| Unique vendors                       |         **43** |
| Total credits                        |  **₹5,09,774** |
| Total debits                         | **₹16,78,901** |
| E-commerce spending share            |      **36.0%** |
| Highest-spending vendor              |     **Amazon** |
| Amazon spending                      |  **₹3,28,530** |
| Anomalous transactions               |         **33** |
| Spending archetypes identified       |          **2** |

---

## 💡 Key Insights

The analysis shows that **E-commerce represents a significant portion of the analysed spending**, accounting for approximately **36%**.

**Amazon** was the highest-spending vendor in the current analysis.

The anomaly detection component identified **33 transactions** that were unusually large relative to their spending categories.

The behavioural classification also identified **The Shopaholic** and **The YOLO Spender** archetypes.

---

## ▶️ How to Run the Project

### Option 1 — Google Colab

1. Download or clone this repository.
2. Upload `SpendDNA.ipynb` to Google Colab.
3. Upload `DADS MP2 Dataset.csv`.
4. Open the notebook.
5. Run the cells from top to bottom.

### Option 2 — Jupyter Notebook

Install the required packages:

```bash
pip install -r requirements.txt
```

Launch Jupyter:

```bash
jupyter notebook
```

Open:

```text
SpendDNA.ipynb
```

Make sure the dataset is in the same directory as the notebook.

---

## 📦 Requirements

The main Python libraries used are:

```text
pandas
numpy
jupyter
```

Install them using:

```bash
pip install -r requirements.txt
```

---

## ⚠️ Data Quality Note

The current notebook output reports **743 unparseable dates**.

Therefore, the date-related analysis should be reviewed and improved before considering the project production-ready.

Some anomaly records may also contain missing date values as a consequence of the date-parsing issue.

This repository represents the current project implementation and analysis output.

---

## 🔐 Data Privacy

The dataset included in this repository is project/synthetic data.

**Do not upload personal bank statements, UPI transaction histories, account numbers, card numbers, or other sensitive financial information to a public GitHub repository.**

---

## 📚 Skills Demonstrated

Through this project, I worked with:

* Python Programming
* Pandas
* NumPy
* Data Cleaning
* Data Preprocessing
* Exploratory Data Analysis
* Transaction Analytics
* Merchant Normalization
* Data Categorization
* Trend Analysis
* Time-Based Analysis
* Anomaly Detection
* Rule-Based Classification
* Financial/FinTech Analytics


## ⭐ Project

If you find this project useful or interesting, feel free to ⭐ the repository and explore the notebook.

**SpendDNA — Turning transaction data into spending insights.** 💳📊
