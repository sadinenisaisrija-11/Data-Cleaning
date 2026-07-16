# Data-Cleaning
# Data Cleaning Project using Python

## 📌 Project Overview

This project demonstrates professional data cleaning techniques using Python and Pandas. The objective is to transform a raw, messy dataset into a clean, analysis-ready dataset by identifying and resolving common data quality issues such as missing values, duplicates, inconsistent formatting, outliers, and incorrect data types.

---

## 🎯 Objective

- Analyze the quality of the dataset.
- Handle missing values using appropriate techniques.
- Identify and remove duplicate records.
- Standardize inconsistent data formatting.
- Detect and handle outliers using the IQR method.
- Correct data types.
- Generate a before vs. after cleaning summary.
- Export the cleaned dataset.

---

## 📂 Dataset

**Dataset:** Titanic Dataset

The dataset contains passenger information from the Titanic disaster, including:

- Passenger ID
- Survival Status
- Passenger Class
- Name
- Gender
- Age
- Ticket Number
- Fare
- Cabin
- Embarkation Port

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📊 Data Cleaning Workflow

### 1. Data Loading
- Loaded the Titanic dataset using Pandas.
- Explored the dataset using `head()`, `info()`, `describe()`, and `shape()`.

### 2. Data Quality Report
- Checked missing values.
- Identified duplicate rows.
- Verified data types.
- Reviewed numerical value ranges.

### 3. Missing Value Handling
Applied appropriate techniques for each column:

- **Age** → Median Imputation
- **Embarked** → Mode Imputation
- **Cabin** → Filled missing values with `"Unknown"`

### 4. Duplicate Removal
- Checked for duplicate rows.
- Removed duplicate records if found.
- Documented the number of duplicates removed.

### 5. Data Standardization
- Standardized categorical values (e.g., `male` → `Male`, `female` → `Female`).
- Ensured consistent formatting throughout the dataset.

### 6. Outlier Detection
- Applied the **Interquartile Range (IQR)** method.
- Identified outliers in numerical columns.
- Capped extreme values where appropriate.

### 7. Data Type Correction
Verified and corrected data types where necessary.

### 8. Before vs. After Comparison
Compared the dataset before and after cleaning using:

- Number of rows
- Number of missing values
- Duplicate count
- Data types

### 9. Export
Saved the cleaned dataset as:

```
Cleaned_Titanic.csv
```

---

## 📈 Results

The dataset was successfully cleaned and transformed into an analysis-ready format.

### Key Improvements

- Missing values handled
- Duplicate records removed
- Standardized categorical values
- Outliers detected and treated
- Correct data types maintained
- Clean dataset exported successfully

---

## 📁 Project Structure

```
Data-Cleaning-Project/
│
├── Data_Cleaning.ipynb
├── Cleaned_Titanic.csv
├── README.md
├── requirements.txt
└── images/
```

---

## 🚀 How to Run

1. Clone the repository.

```bash
git clone https://github.com/your-username/data-cleaning-project.git
```

2. Install the required libraries.

```bash
pip install -r requirements.txt
```

3. Open the notebook.

```bash
jupyter notebook
```

4. Run all notebook cells.

---

## 📌 Future Improvements

- Automate data cleaning using reusable functions.
- Build a Streamlit application for interactive data cleaning.
- Integrate advanced outlier detection techniques.
- Generate automated data quality reports.

---

## 📄 Requirements

```
pandas
numpy
matplotlib
seaborn
jupyter
```

