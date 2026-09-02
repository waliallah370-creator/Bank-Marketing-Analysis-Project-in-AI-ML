# 🏦 Bank Marketing Analysis & Machine Learning Preprocessing Pipeline

## 📌 Project Overview

This project presents a complete end-to-end Data Science and Machine Learning preprocessing pipeline using the **Bank Marketing Dataset**. The objective is to analyze customer and campaign data from a Portuguese banking institution and prepare the dataset for machine learning applications.

The project follows a structured workflow from raw data exploration to a fully integrated Scikit-Learn preprocessing pipeline, covering all essential stages of data preprocessing and feature engineering.

---

## 🎯 Project Objective

The primary goal of this project is to analyze customer behavior and identify the factors that influence whether a client subscribes to a bank term deposit.

### Target Variable

**y** → Has the client subscribed to a term deposit?

* Yes = Subscribed
* No = Not Subscribed

---

## 📊 Dataset Information

* **Dataset Name:** Bank Marketing Dataset
* **Source:** UCI Machine Learning Repository / Kaggle
* **Rows:** 45,211
* **Columns:** 17
* **Problem Type:** Binary Classification

### Key Features

#### Customer Information

* Age
* Job
* Marital Status
* Education
* Balance
* Housing Loan
* Personal Loan
* Credit Default Status

#### Campaign Information

* Contact Type
* Contact Month
* Contact Day
* Campaign Contacts
* Previous Contacts
* Previous Campaign Outcome
* Call Duration

---

## 🔄 End-to-End Pipeline Architecture

This project follows a complete Machine Learning preprocessing workflow:

### 1️⃣ Dataset Understanding

* Dataset background and business objective
* Feature identification
* Target variable analysis
* Dataset structure inspection

### 2️⃣ NumPy Analysis

* Array conversion
* Indexing and slicing
* Statistical calculations
* Conditional filtering
* Matrix operations

### 3️⃣ Pandas Exploration

* Data inspection
* Data types analysis
* Sorting and filtering
* Aggregations and grouping
* Duplicate detection

### 4️⃣ Matplotlib Visualization

* Age distribution analysis
* Balance distribution
* Campaign activity visualization
* Feature trend exploration

### 5️⃣ Seaborn Statistical Analysis

* Count plots
* Box plots
* Correlation heatmaps
* Customer behavior comparisons

### 6️⃣ Missing Value Investigation

* Missing value detection
* Percentage analysis
* Pandas-based handling
* Scikit-Learn SimpleImputer implementation

### 7️⃣ Feature Encoding

* Binary Encoding
* Label Encoding
* One-Hot Encoding
* Feature transformation validation

### 8️⃣ Outlier Detection & Treatment

* IQR Method
* Outlier identification
* Distribution analysis
* Outlier capping strategy

### 9️⃣ Feature Scaling

* StandardScaler
* MinMaxScaler
* Scaling comparison
* Performance considerations

### 🔟 Scikit-Learn Pipeline

* Pipeline creation
* ColumnTransformer implementation
* Automated preprocessing workflow
* Data leakage prevention

### 1️⃣1️⃣ Final Verification

* Shape validation
* Missing value verification
* Transformation consistency checks
* Pipeline output inspection

---

## 🛠️ Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

---

## 📂 Project Structure

```text
Bank-Marketing-Analysis/
│
├── Bank_Marketing_Analysis.ipynb
├── bank-full.csv
├── README.md
│
├── images/
│   ├── age_distribution.png
│   ├── balance_distribution.png
│   ├── heatmap.png
│   └── boxplot.png
│
└── requirements.txt
```

---

## 📈 Key Insights

* Most customers did not subscribe to term deposits.
* Customer balance shows a highly skewed distribution.
* Previous campaign outcomes strongly influence future subscription behavior.
* Call duration appears to be one of the most influential variables.
* Several numerical features contain significant outliers.
* Proper encoding and scaling improve data readiness for machine learning models.

---

## 🚀 Skills Demonstrated

✔ Data Cleaning

✔ Exploratory Data Analysis (EDA)

✔ Statistical Analysis

✔ Data Visualization

✔ Feature Engineering

✔ Missing Value Handling

✔ Outlier Detection

✔ Feature Scaling

✔ Scikit-Learn Pipelines

✔ Machine Learning Preprocessing

---

## 🎓 Learning Outcomes

Through this project, I gained hands-on experience in building a complete machine learning preprocessing pipeline while applying industry-standard data science practices for real-world banking data.

The project demonstrates the ability to transform raw data into a machine-learning-ready dataset using structured preprocessing, feature engineering, and validation techniques.

---

## 👨‍💻 Author

**Neha**

Data Science & Machine Learning Enthusiast

Focused on building practical end-to-end data analytics and machine learning projects to strengthen real-world problem-solving skills.

---

## ⭐ If you found this project useful, consider giving it a star on GitHub!
