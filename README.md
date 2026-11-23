
# ETL Operations Using Python

## Overview

This assignment focuses on performing **Extract, Transform, and Load (ETL)** operations using Python. It involves working with CSV datasets, performing data cleaning, handling missing values, filtering records, generating statistical summaries, and performing data aggregation using Pandas and NumPy.

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy

## Files Included

| File | Description |
|---|---|
| `Question_01.ipynb` | Employee dataset creation and data manipulation |
| `Question_02.ipynb` | Employee salary dataset ETL operations |
| `employee_salary.csv` | Original employee salary dataset |
| `cleaned_Employee.csv` | Cleaned and processed employee dataset |

## Tasks Performed

### Question 01 – Employee Dataset Operations

- Create an employee dataset using Python.
- Rename DataFrame columns.
- Handle missing numerical values using mean imputation.
- Handle missing department values using mode.
- Filter employees working in the IT department.
- Filter employees earning more than 60,000.
- Calculate average salary.
- Calculate department-wise average salary.

### Question 02 – Employee Salary ETL Operations

#### 1. Extraction

- Import CSV dataset using Pandas.
- Display the first 10 records.
- Identify the number of rows and columns.
- Examine column data types.

#### 2. Transformation

- Remove duplicate records.
- Handle missing values.
- Generate statistical summaries.
- Identify maximum age.
- Find the lowest salary.
- Identify the department with the maximum number of employees.
- Filter employees based on age.
- Calculate annual salary.
- Create a DataFrame containing female employee details.
- Find unique education levels.
- Calculate city-wise employee counts.
- Filter male employees earning more than 50,000.

#### 3. Aggregation

- Calculate total revenue by region.
- Calculate total revenue by product.
- Identify the highest-revenue product.
- Calculate average transaction value.

#### 4. Loading

- Export cleaned and processed data into CSV format.

## Key Concepts Covered

- ETL Workflow
- CSV File Handling
- DataFrame Operations
- Data Cleaning and Preprocessing
- Missing Value Handling
- Duplicate Removal
- Data Filtering
- Column Renaming
- Statistical Analysis
- GroupBy and Aggregation
- Data Export

## How to Run

### 1. Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scipy
```

### 2. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 3. Open the Notebooks

- `Question_01.ipynb`
- `Question_02.ipynb`

### 4. Execute the Cells

Run the notebook cells sequentially.

Make sure the required CSV files are available in the same working directory as the notebooks.

## Learning Outcomes

- Gained practical experience in handling structured CSV datasets.
- Understood the ETL process using Python.
- Practiced data cleaning and preprocessing techniques.
- Learned to perform filtering, statistical analysis, and aggregation using Pandas.
- Developed experience in exporting processed datasets.

---

**Focus Areas:** Python | Pandas | NumPy | Data Cleaning | ETL | Data Analytics
