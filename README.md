# Employee Data Analysis

This repository contains a Jupyter Notebook (`Employee data queried.ipynb`) that performs an exploratory data analysis on employee data. The analysis covers various aspects of the workforce, including demographics, performance metrics, and departmental distributions.

## Overview

The notebook reads an employee dataset from a CSV file and performs several analyses to answer key questions about the workforce. The dataset includes information such as employee IDs, names, start and exit dates, job titles, business units, performance scores, and demographic details.

## Key Analyses

1. **Employee Status**: Counts of active vs. terminated employees.
2. **Job Titles**: Identifies the top 5 most common job titles.
3. **Business Units**: Distribution of employees across different business units.
4. **Hiring Trends**: Number of employees hired each year.
5. **Performance Metrics**: Average employee ratings per department and job titles with the highest performance scores.
6. **Demographics**: Gender and racial breakdowns, marital status distributions, and average age.
7. **Geographical Data**: States with the highest number of employees and performance metrics across locations.

## Findings

- **Active Employees**: 2,458 employees are active, while 321 voluntarily terminated and 66 were terminated for cause.
- **Top Job Titles**: "Production Technician I" is the most common job title.
- **Business Units**: Employees are evenly distributed across business units, with counts ranging from 294 to 304.
- **Hiring Trends**: The highest number of employees were hired in 2022 (620), followed by 2021 (600).
- **Performance Scores**: The "Admin Offices" department has the highest average employee rating.
- **Demographics**: The workforce is 56% female and 44% male, with a diverse racial composition (Asian, Black, White, Other, Hispanic).
- **Geographical Data**: Massachusetts (MA) has the highest number of employees (2,651).

## Usage

1. **Prerequisites**: Ensure you have Python and Jupyter Notebook installed, along with the required libraries (`pandas`, `numpy`, `seaborn`, `matplotlib`).
2. **Data**: Place the `employee_data.csv` file in the specified path or update the path in the notebook.
3. **Run the Notebook**: Open the notebook in Jupyter and execute the cells to reproduce the analysis.

## Repository Structure

- `Employee data queried.ipynb`: The main notebook containing the analysis.
- `employee_data.csv`: The dataset used for analysis 

## Future Work

- Expand the analysis to include more detailed visualizations.
- Incorporate predictive modeling to forecast employee turnover.
- Explore correlations between performance scores and other variables in greater depth.

Feel free to explore the notebook and adapt it for your own datasets or analyses!
