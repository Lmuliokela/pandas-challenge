# Pandas-Challenge

---

## Description

**Description:** This challenge was fro me to assume the role of a new Chief Data Scientist for my city's school district. In this capacity, to be helping the school board and mayor make strategic decisions regarding future school budgets and priorities. As a first task, I been asked to analyze the district-wide standardized test results and being given access to every student's math and reading scores, as well as various information on the schools they attend. My task is to aggregate the data to showcase obvious trends in school performance.

---

## Set-UP

- Two csv files were provided for students and schools with all the necessary date needed for the analysis
- A strter code was also given via jupyter notebook that I had to import
- A sample solution called "PyCitySchools_starter.ipynb" was also  provided for reference sake and hints
- Created a repo in github and pushed my files via download as i had challenges with my git push

---

## Dependencies

- import pandas as pd
  
  from pathlib import Path

- Read School and Student Data File and store into Pandas DataFrames
  
  school_data = pd.read_csv(school_data_to_load)

  student_data = pd.read_csv(student_data_to_load)

- Combine the data into a single dataset
  
  school_data_complete = pd.merge(student_data, school_data, how="left", on=["school_name", "school_name"])
  
  school_data_complete.head()

---

## Analysis

- District Summary
- School Summary
- Highest-Performing Schools (by % Overall Passing)
- Lowest-Performing Schools (by % Overall Passing)
- Math Scores by Grade
- Reading Scores by Grade
- Scores by School Spending
- Scores by School Size
- Scores by School Type
  




