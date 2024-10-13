# AMCAT Data Analysis Project

## Overview

This project is an analysis of an AMCAT dataset, focusing on various insights related to job placement, salaries, academic performance, and personality traits. The dataset contains information about individuals' educational background, job designations, salary, performance in standardized tests, and personality factors.

The goal of the project is to perform exploratory data analysis (EDA) to uncover patterns, trends, and correlations that can help in understanding the factors influencing job placement and salary levels.

---

## Key Features of the Dataset

- **Total Entries:** 3998 records
- **Attributes:** 38 features, including:
  - **Demographics:** Gender, Date of Birth (DOB)
  - **Education:** 10th and 12th percentages, Board of Education, Graduation Year, College GPA, Specialization
  - **Job Details:** Salary, Designation, Job City, Date of Joining (DOJ), Date of Leaving (DOL)
  - **Skills:** English, Logical, Quantitative, and Domain expertise scores
  - **Personality Traits:** Conscientiousness, Agreeableness, Extraversion, Neuroticism, Openness to Experience

---

## Exploratory Data Analysis (EDA)

### Data Cleaning

- **Missing Values:** The dataset has no missing values.
- **Duplicates:** No duplicate records were found.

---

### Univariate Analysis

- **Salary Distribution:**
  - The average salary is ₹307,699.8, with a standard deviation of ₹212,737.5.
  - The salary range is from ₹34,000 to ₹4,000,000.
  - Salaries are more concentrated below ₹100,000, with fewer high salaries above ₹300,000.

- **College GPA:**
  - The average GPA of students is **7.15**.

- **Specializations:**
  - The most common specializations are:
    1. Electronics and Communication Engineering (880)
    2. Computer Science & Engineering (744)
    3. Information Technology (660)
    4. Computer Engineering (600)

- **Job Cities:**
  - **Top cities** where most jobs are located:
    - Bangalore (627 jobs)
    - Noida (368 jobs)
    - Hyderabad (335 jobs)
    - Pune (290 jobs)

---

### Insights

- **Salaries:** The majority of salaries are concentrated in lower ranges (below ₹100,000), with a sharp decline in the number of higher-paying jobs (above ₹300,000).
- **Specializations:** A higher number of individuals have specializations in Electronics and Communication, Computer Science, and Information Technology.
- **Job Locations:** Bangalore is the most common city for job placements, followed by Noida and Hyderabad.
- **Personality Traits:** The dataset also contains information about candidates’ personality traits, which can provide insights into how personality factors may influence job placement and performance.

---

## Visualizations

- **Salary Distribution:** Kernel Density Estimate (KDE) plot to show salary concentration.
- **Top Specializations:** Bar plot showing the distribution of the most common specializations.
- **Job City Distribution:** Bar chart highlighting the count of job placements across different cities.

---

## Conclusion

The AMCAT dataset provides valuable insights into how academic background, job locations, and personality traits impact job placements and salaries. The findings from this analysis can help in understanding patterns that may influence job outcomes in the technology and engineering sectors.

---

## Future Work

- **Predictive Analysis:** Use machine learning models to predict salary ranges based on factors like specialization, GPA, and personality traits.
- **Clustering Analysis:** Group individuals based on similar traits and academic backgrounds to uncover further insights into job placements.
- **Time-based Analysis:** Study how job placements and salaries have changed over time, based on Date of Joining (DOJ) and Graduation Year.

---

## Technologies Used

- **Python:** Pandas, NumPy, Seaborn, Matplotlib
- **Data Analysis:** Exploratory data analysis using descriptive statistics and visualizations
- **Libraries:** SciPy for statistical analysis

