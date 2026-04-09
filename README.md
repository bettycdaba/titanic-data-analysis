#Task 3

## Overview

This project analyzes the Titanic dataset using **pandas**.
It includes creating a custom dataset and performing data analysis on a real-world dataset.

## Part 1: Custom Dataset

* Created a dataset using a Python dictionary
* Converted it into a pandas DataFrame
* Included:

  * 5 columns (features)
  * 15 rows
  * Custom index
  
## Part 2: Titanic Dataset Analysis

### Step 1: Data Exploration

* Used `.head()` to view the first rows
* Used `.info()` to check data types and missing values
* Used `.describe()` for statistical summary

### Step 2: Data Cleaning

* Filled missing values:

  * **Age** → median
  * **Embarked** → mode
* Dropped **Cabin** column (too many missing values)
* Removed duplicate rows

### Step 3: Data Analysis

Used `groupby()` to analyze:

* Survival rate by gender
* Survival rate by passenger class
* Average age per class
* Survival rate by age group

### Step 4: Filtering

* Female passengers who survived
* Children who survived
* First-class passengers with high survival rate

## Key Insights

* **Females were more likely to survive than males**
* **Passenger class affected survival**

  * 1st class → highest survival
  * 3rd class → lowest survival
* **Children were prioritized during rescue**
* **Highest survival group: Female + 1st Class + Child**


## Tools Used

* Python
* pandas
* Google Colab

## File Included

* `titanic_analysis.ipynb`

## How to Run

1. Open the notebook in Google Colab
2. Run all cells
3. View results and outputs

## Project Link

https://github.com/bettycdaba/titanic-data-analysis

