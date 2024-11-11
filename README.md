# Module 4: pandas-challenge

## The Task
Taking on the role of the new Chief Data Scientist for my city's school district, I'll be helping the school board and mayor make strategic decisions regarding future school budgets and priorities.
As a first task, I've been asked to analyze the district-wide standardized test results. I've be given access to every student's math and reading scores, as well as various information on the schools they attend. My task is to aggregate the data to showcase obvious trends in school performance.

## User Story
```md
AS A school district data scientist
I WANT to be able to aggregate and analyze high school test results
SO THAT I can identify trends in school performance.
```

## Acceptance Criteria
```md
DISTRICT SUMMARY
  * Calculate the total number of unique schools
  * Calculate the total number of students 
  * Calculate the total budget 
  * Calculate the average (mean) math score 
  * Calculate the average (mean) reading score 
  * Use the code provided to calculate the percentage of students who passed math
  * Calculate the percentage of students who passed reading
  * Use the code provided to calculate the percentage of students that passed both math and reading
  * Create a new DataFrame for the above calculations called district_summary 

SCHOOL SUMMARY
  * Use the code provided to select the school type
  * Calculate the total student count
  * Use the code provided to calculate the per capita spending
  * Calculate the average test scores
  * Calculate the number of schools with math scores of 70 or higher
  * Calculate the number of schools with reading scores of 70 or higher
  * Use the provided code to calculate the schools that passed both math and reading with scores of 70 or higher
  * Use the provided code to calculate the passing rates 
  * Create a new DataFrame for the above calculations called per_school_summary 

HIGHEST-PERFORMING SCHOOLS BY PERCENTAGE OF OVERALL PASSING 
  * Sort the schools by % Overall Passing in descending order 
  * Save the results to a DataFrame called top_schools 
  * Display the first 5 rows 

LOWEST-PERFORMING SCHOOLS BY PERCENTAGE OF OVERALL PASSING 
  * Sort the schools by % Overall Passing in ascending order 
  * Save the results to a DataFrame called bottom_schools 
  * Display the first 5 rows 

MATH SCORES BY GRADE
  * Use the code provided to separate the data by grade 
  * Group by "school_name" and take the mean of each 
  * Use the code to select only the math_score 
  * Combine each of the scores above into single DataFrame called math_scores_by_grade 

READING SCORES BY GRADE 
  * Use the code provided to separate the data by grade 
  * Group by "school_name" and take the mean of each 
  * Use the code to select only the reading_score 
  * Combine each of the scores above into single DataFrame called reading_scores_by_grade 

SCORES BY SCHOOL SPENDING 
  * Use pd.cut with the provided code to bin the data by the spending ranges 
  * Use the code provided to calculate the averages 
  * Create the spending_summary DataFrame using the binned and averaged spending data 

SCORES BY SCHOOL SIZE 
  * Use pd.cut with the provided code to bin the data by the school sizes 
  * Use the code provided to calculate the averages 
  * Create the size_summary DataFrame using the binned and averaged size data 

SCORES BY SCHOOL TYPE 
  * Group the per_school_summary DataFrame by "School Type" and average the results 
  * Use the code provided to select the new column data 
  * Create a new DataFrame called type_summary that uses the new column data 

WRITTEN REPORT 
  * The written report presents a cohesive written analysis that:
    * Summarizes the analysis
    * Draws two correct conclusions or comparisons from the calculations
```

## Examples of Use
### District Summary:
![A DataFrame summarizing the dataset from the school district as a whole.](../Resources/district-summary.png)

### School Summary:
![A DataFrame summarizing key statistics for each school in the district.](../Resources/school-summary.png)

### Scores by School Size
![A DataFrame summarizing key statistics by aggregated school population.](../Resources/scores-by-size.png)

### Scores by School Type
![A DataFrame summarizing key statistics by aggregated school type.](../Resources/scores-by-type.png)

## License
This project is licensed under the GNU General Public License v3.0.  
License Link:
https://www.gnu.org/licenses/gpl-3.0.en.html   
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
