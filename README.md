# Stack Overflow Survey — Missing Values Analysis & Employment Imputation

This project works with a Stack Overflow Developer Survey dataset and focuses on
exploring the dataset, identifying missing values, imputing missing entries in
the Employment column using the most frequent value (mode), and visualizing the
top 5 Employment categories after imputation.

## 📌 Tasks Performed in This Project

### ✅ Task 1 — Load the Dataset
- Loaded the dataset from a file path into a Pandas DataFrame.

### ✅ Task 2 — Explore the Dataset
- Checked dataset shape (rows and columns)
- Viewed column names
- Displayed dataset info
- Generated summary statistics
- Viewed sample rows (head and tail)

### ✅ Task 3 — Finding Missing Values
- Counted missing values per column
- Identified columns that contain missing values
- Counted:
  - number of columns with missing values
  - total missing values in the whole dataset
- Created a heatmap of missing values for selected columns

### ✅ Task 4 — Imputing Missing Values (Employment Column)
- Found the most frequent Employment value (mode)
- Counted how many times it appears
- Filled missing Employment values using the mode

### ✅ Task 5 — Visualizing Imputed Data
- Plotted a bar chart of the **Top 5 Employment categories**
- Added value labels to the bars

## 🧰 Libraries Used
- Python
- Pandas
- Matplotlib
- Seaborn

## ▶️ How to Run
1. Open the notebook file in Jupyter / JupyterLab
2. Install dependencies if needed:
3. 3. Run the notebook cells step by step

## 🎯 Project Focus
This project is focused only on:
- dataset exploration
- missing value inspection
- Employment column imputation
- visualization of Employment distribution

