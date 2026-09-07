
## ABC Company Employee Data Analysis

##  Project Overview

This project analyzes employee data from **ABC Company** to understand the distribution of employees across different teams and positions, employee age groups, and salary expenditure.

The dataset contains **458 employee records and 9 columns**. Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn were used for data preprocessing, analysis, and visualization.

---

## Project Objectives

The main objectives of this project are:

* To preprocess and clean the employee dataset.
* To correct the values in the `height` column.
* To analyze the distribution of employees across different teams.
* To calculate the percentage of employees in each team.
* To analyze employees based on their positions.
* To identify the predominant age group among employees.
* To identify the team and position with the highest salary expenditure.
* To analyze the correlation between employee age and salary.
* To represent the analysis using appropriate visualizations.
* To communicate the findings through a data-driven story.

---

##  Technologies and Libraries Used

* **Python**
* **Pandas** – Data manipulation and analysis
* **NumPy** – Numerical operations and random value generation
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical data visualization
* **Google Colab** – Development and analysis environment

---


##  Data Preprocessing

During preprocessing, the `height` column was corrected as instructed in the project requirements.

The existing height values were replaced with randomly generated values between **150 cm and 180 cm**.


Additional checks were performed to understand the structure of the dataset, including:

* Number of rows and columns
* Data types
* Missing values
* Duplicate records

---

##  Analysis

## Employee Distribution Across Teams

The number of employees in each team was calculated along with their percentage of the total workforce.


### 2. Employee Distribution by Position

Employees were grouped according to their positions to identify the number of employees in each role.


### 3. Salary Expenditure

Salary expenditure was analyzed based on:

* Team
* Position
* Team and Position combination

The total salary was calculated using the `groupby()` function.


### 4. Age and Salary Correlation

The relationship between employee age and salary was analyzed using Pearson correlation.

A histogram plot was used to visually represent the relationship between age and salary.



## Key Insights / Data Story

The analysis provides several insights into ABC Company's workforce:

1. Employee distribution varies across teams, with some teams having significantly more employees than others.
2. Certain positions have a higher representation within the organization.
3. The predominant age group provides an understanding of the overall age profile of the workforce.
4. Salary expenditure is concentrated in particular teams and positions.
5. The relationship between age and salary can be observed through the correlation analysis and hist plot.

Overall, the analysis provides a better understanding of the company's workforce structure and salary distribution.

---

##  Project Structure


ABC-Company-Employee-Analysis
│
├── employee_data.csv
├── ABC_Company_Employee_Analysis.ipynb
├── README.md
└── requirements.txt



##  Conclusion

This project demonstrates the use of Python for data preprocessing, exploratory data analysis, statistical analysis, and data visualization.

The analysis helps identify workforce distribution, predominant employee age groups, salary expenditure patterns, and the relationship between age and salary.


