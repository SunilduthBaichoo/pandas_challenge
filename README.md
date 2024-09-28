# pandas_challenge
---

# PyCitySchools Analysis

## Project Overview
This project involves the analysis of district-wide standardized test results for the city's school district. The data provides insights into student performance across schools and helps the school board and mayor make informed decisions about future school budgets and strategic priorities. The analysis is done using **Pandas** and **Jupyter Notebook** and focuses on aggregating data to showcase trends in school performance based on math and reading scores.

## Objective
The goal of this project is to create a high-level report for the school district that summarizes school performance based on various metrics such as test scores, school spending, and school size. Additionally, this report identifies the highest- and lowest-performing schools in terms of student performance.

## Files
- **`PyCitySchools_main_final.ipynb`**: The main Jupyter notebook that contains the code for performing the analysis.
- **`schools_complete.csv`** and **`students_complete.csv`**: These files contain data on schools, students, and their respective performance in math and reading.
- **`README.md`**: This file, describing the project and its objectives.
  
## Data Overview
The dataset includes information on the following:
- **Student information**: Student names, gender, grade level, math and reading scores.
- **School information**: School names, school type (e.g., District or Charter), student count, budget, and spending per student.

## Analysis Process
The analysis is broken down into several steps, each focusing on different aspects of school performance. The key metrics calculated include:
1. **District Summary**:
   - Total number of unique schools
   - Total number of students
   - Total budget
   - Average math and reading scores
   - Percent of students passing math and reading
   - Overall passing percentage (students passing both math and reading)

2. **School Summary**:
   - School name and type (District or Charter)
   - Total student count
   - School budget and per-student spending
   - Average math and reading scores
   - Percentage of students passing math and reading, and overall passing rates

3. **Top and Bottom Performing Schools**:
   - Identifies the 5 highest- and lowest-performing schools based on the overall passing rate.

4. **Scores by Grade**:
   - Breakdown of average math and reading scores for each grade (9th, 10th, 11th, and 12th) in each school.

5. **Scores by School Spending**:
   - Performance metrics based on average spending per student, categorized into four spending ranges.

6. **Scores by School Size**:
   - School performance broken down by three size categories: Small (<1000 students), Medium (1000-2000 students), and Large (2000-5000 students).

7. **Scores by School Type**:
   - Comparison of performance metrics based on school type (District or Charter).

## Tools Used
- **Pandas**: Used for data manipulation, aggregation, and analysis.
- **Jupyter Notebook**: The main environment used for writing, running, and visualizing the analysis.

## Results
The final output includes multiple DataFrames summarizing the key metrics:
- **District Summary**
- **School Summary**
- **Top 5 and Bottom 5 Performing Schools**
- **Math and Reading Scores by Grade**
- **Scores by School Spending, Size, and Type**

## Key Trends and Insights
1. **Charter Schools Outperform District Schools**: Charter schools generally show higher average passing rates in both math and reading, along with a higher overall passing rate compared to district schools.
2. **Spending Per Student Doesn't Correlate Directly with Performance**: Schools with lower spending per student often outperform those with higher spending, suggesting that factors other than budget contribute significantly to student performance.

## Conclusion
This analysis provides the school district with valuable insights into school performance, highlighting both high- and low-performing schools. It enables data-driven decisions for future resource allocation and strategic planning.

---

By providing this structured `README.md`, users of the project will understand its purpose, contents, and how to run the analysis.
