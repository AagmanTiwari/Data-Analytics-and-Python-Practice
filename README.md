
# Python Programming and Data Analytics Practice

## Overview

This repository contains hands-on Python assignments and practical exercises focused on data manipulation, data cleaning, ETL operations, probability, and statistical analysis using Python libraries.

The objective is to strengthen programming fundamentals and develop practical experience in solving data-related problems.

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy

---

# Day 01 – ETL Operations Using Python

## Overview

This assignment focuses on performing **Extract, Transform, and Load (ETL)** operations using Python. It involves working with CSV datasets, performing data cleaning, handling missing values, filtering records, generating statistical summaries, and performing data aggregation using Pandas and NumPy.

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

---

# Day 02 – Probability and Conditional Probability

## Overview

This section focuses on understanding and implementing probability and conditional probability concepts using Python and Pandas.

The exercises cover practical scenarios involving customer purchasing behavior, student examination results, Titanic passenger survival analysis, medical testing, and Bayes' Theorem.

## Files Included

| File | Description |
|---|---|
| `Question-01.ipynb` | Customer purchase probability based on gender |
| `Question-02.ipynb` | Student passing probability based on gender |
| `Question-03.ipynb` | Titanic survival probability based on gender |
| `Question-04.ipynb` | Medical test probability and Bayes' Theorem |
| `Question-05.ipynb` | Student performance probability based on gender |


## Questions and Tasks

### Question 01 – Customer Purchase Probability

A company collected purchase information from 100 customers.

| Gender | Purchased | Not Purchased |
|---|---:|---:|
| Male | 30 | 20 |
| Female | 35 | 15 |

**Task:**

- Calculate the probability of purchase given that the customer is female.

**Concept:** Conditional Probability

### Question 02 – Student Passing Probability

Create a student dataset using Pandas containing gender and examination results.

**Task:**

- Create a Pandas DataFrame.
- Calculate the probability of passing given that the student is female.

**Concept:** Conditional Probability and DataFrame Filtering

### Question 03 – Titanic Survival Analysis

Using the Titanic dataset, calculate the probability of survival given that the passenger was female.

**Tasks:**

- Load the Titanic dataset using Seaborn.
- Filter female passengers.
- Identify female passengers who survived.
- Calculate the conditional probability of survival given gender.

**Concept:** Conditional Probability and Real-World Dataset Analysis

### Question 04 – Medical Test and Bayes' Theorem

A hospital conducted a health screening of 1,000 people.

| Category | Number of People |
|---|---:|
| People with disease | 200 |
| People without disease | 800 |
| Tested positive among diseased | 180 |
| Tested positive among healthy | 80 |

**Tasks:**

- Calculate the probability that a person has the disease given a positive test result.
- Calculate the probability that a person does not have the disease given a negative test result.
- Calculate the probability of testing positive.
- Explain why a positive test result does not necessarily mean that the person has the disease.

**Concepts:** Conditional Probability and Bayes' Theorem

### Question 05 – Student Performance Probability

Create the following dataset using Pandas.

| Student | Gender | Passed |
|---|---|---|
| A | Male | Yes |
| B | Female | Yes |
| C | Male | No |
| D | Female | Yes |
| E | Male | Yes |
| F | Female | No |
| G | Male | Yes |
| H | Female | No |
| I | Male | No |
| J | Female | Yes |

**Tasks:**

1. Create a Pandas DataFrame.
2. Calculate the probability of passing.
3. Calculate the probability of passing given that the student is female.
4. Calculate the probability of passing given that the student is male.

**Concepts:** Basic Probability, Conditional Probability, and Pandas DataFrame Operations

## Key Concepts Covered

- Basic Probability
- Conditional Probability
- Bayes' Theorem
- Probability Calculations
- DataFrame Creation
- Data Filtering
- Boolean Indexing
- Statistical Analysis
- Real-World Data Analysis

---

## How to Run

### 1. Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scipy jupyter
```

### 2. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 3. Open the Required Notebook

Navigate to the respective assignment folder and open the required `.ipynb` file.

### 4. Execute the Cells

Run the notebook cells sequentially.

Make sure the required CSV files are available in the same working directory whenever applicable.

## Learning Outcomes

- Gained practical experience in Python programming.
- Understood ETL operations using Pandas and NumPy.
- Practiced data cleaning and preprocessing techniques.
- Learned to perform filtering, statistical analysis, and aggregation.
- Understood probability and conditional probability.
- Applied Bayes' Theorem to a real-world medical testing scenario.
- Developed problem-solving skills through practical exercises.

---

**Focus Areas:** Python | Pandas | NumPy | ETL | Data Cleaning | Probability | Conditional Probability | Bayes' Theorem | Data Analytics
