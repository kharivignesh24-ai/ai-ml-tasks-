# Task 2: Data Cleaning & Missing Value Handling

## 📌 Overview
This project focuses on cleaning a dataset by identifying and handling missing values using Python.  
The goal is to improve data quality and make the dataset ready for further analysis or machine learning tasks.

The task was implemented using **Google Colab** and standard data analysis libraries.

---

## 🛠 Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Google Colab

---

## 📂 Dataset
The project was performed on a structured CSV dataset : titanic.csv file is used 

---

## 🔍 Steps Performed

### 1️⃣ Load the Dataset
- Imported the dataset using Pandas.
- Viewed initial rows and dataset structure using `head()` and `info()`.

### 2️⃣ Identify Missing Values
- Used `isnull().sum()` to detect missing values in each column.

### 3️⃣ Visualize Missing Data
- Created bar charts to visualize the number of missing values per column.
- This helped identify columns with high missing data.

### 4️⃣ Handle Numerical Missing Values
- Identified numerical columns using `select_dtypes`.
- Filled missing values using **median imputation** to reduce the impact of outliers.

### 5️⃣ Handle Categorical Missing Values
- Identified categorical columns.
- Filled missing values using **mode imputation**.

### 6️⃣ Remove Columns with High Missing Values
- Dropped columns with more than 50% missing values to maintain data reliability.

### 7️⃣ Validate Cleaned Dataset
- Rechecked missing values to ensure successful cleaning.
- Verified dataset structure and data types.

### 8️⃣ Compare Before vs After
- Compared dataset shape and summary statistics to observe improvements in data quality.

---

## ✅ Outcome
- Missing values were successfully handled.
- Dataset is clean and ready for analysis or model building.
- Improved consistency and reliability of data.

---

## 🚀 How to Run
1. Open the notebook in **Google Colab**
2. Upload the dataset
3. Run all cells sequentially

---

## 📌 Author
**K Harivignesh**  
Task completed as part of daily AI/ML learning activities.
