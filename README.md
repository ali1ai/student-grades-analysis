# Student Grades EDA & Cleaning

This repository contains an end-to-end example of exploratory data analysis (EDA) and cleaning on a synthetic student grades dataset.

## Project Overview

The goal is to practice the complete workflow of working with messy real-world data:

- Generate synthetic student data (First Name, Last Name, Grade).
- Inject common data quality issues:
  - Missing values,
  - Negative grades,
  - Out-of-range values (e.g., 540 instead of 54).
- Perform EDA:
  - Preview data and schema,
  - Summary statistics,
  - Missingness and validity checks,
  - Identify and flag likely errors.
- Clean the data with documented, reproducible rules:
  - Fix obvious 10× typos,
  - Clip grades to valid range,
  - Impute missing grades using the median.
- Visualize the grade distributions before and after cleaning.
- Save cleaned and raw datasets for downstream use.

## Usage

Run the Jupyter notebook `student_grades_eda.ipynb` to reproduce the analysis. It requires:

- Python 3.8+
- pandas
- numpy
- matplotlib

Install dependencies via:

```bash
pip install pandas numpy matplotlib
# student-grades-analysis