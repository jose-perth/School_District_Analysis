# School_District_Analysis

## Overview of Project

This project is the forth weekly challenge of the Data Science Bootcamp. It allows us to put into practice and showcare the skills learned in Module 4 of the bootcamp.

### Purpose

The City School Board has requested analysis on student funding and student standardized test math and reading scores across a number of schools. This analysis will help the School Superintendent and School Board in making decisions regarding future funding and priorities.

The requested information included:

- A high-level snapshot of the district's key metrics, presented in a table format
- An overview of the key metrics for each school, presented in a table format
- Tables presenting each of the following metrics:
  - Top 5 and bottom 5 performing schools, based on the overall passing rate
  - The average math score received by students in each grade level at each school
  - The average reading score received by students in each grade level at each school
  - School performance based on the budget per student
  - School performance based on the school size
  - School performance based on the type of school

Addtionally, the School Board has requested the removal of a number of scores from the final analysis.

## Results

Analysis of the input files was carried out in Python 3.7 using a Jupyter Notebook environment ([Jupyter Notebook](PyCitySchools_Challenge.ipynb)).  

The student score data was cleaned and suspected scores marked as NaN (*Not A Number*) before aggregating to the the school data for the full analysis.

![Workflow diagram](Resources/workflow.png)

The input files **students_complete.csv** and **schools_complete.csv** were provided in CSV format and can be downloaded from the folder [Resources/](Resources/).

Note:  suspected scores included all math and reading scores for 9th Grade students in Thomas High School.

## Summary



Results: Using bulleted lists and images of DataFrames as support, address the following questions.

- How is the district summary affected?
- How is the school summary affected?
- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
- How does replacing the ninth-grade scores affect the following:
    - Math and reading scores by grade
    - Scores by school spending
    - Scores by school size
    - Scores by school type

Summary: Summarize four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.