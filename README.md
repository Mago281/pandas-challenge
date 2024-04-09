Pandas Project:  PyCitySchools
----------------------

## Introduction

***Applying Python Pandas into analysis via Jupyter Notebook.***

This project delves into the utilization of Python Pandas for data analysis within a Jupyter Notebook environment.

The focus lies on creating and manipulating Pandas DataFrames to dissect school-related data alongside standardized test scores.

The PyCitySchools Jupyter Notebook and accompanying Excel files serve as the foundation for this endeavor:

   <img src="https://github.com/Mago281/pandas-challenge/assets/131424690/f77ded6d-6ba1-4b43-b84b-b7df026e0d71" width="160" height="75">


To ensure alignment with the project requirements, I referenced the provided sample solution named PyCitySchools_starter.ipynb.

Utilizing Pandas and Jupyter Notebook, the analysis encompasses a comprehensive report featuring relevant datasets. Additionally, the report offers insights through a written narrative, elucidating two discernible trends extracted from the data.
Using Pandas and Jupyter Notebook, I created a report that included the following data and included a written description of two observable trends based on the data.

---


**Background - Objective & Overview**
----------------------

In my role as the newly appointed Chief Data Scientist for our local government, I am tasked with aiding the school board and mayor in making informed decisions regarding future school budgets and priorities.

My initial assignment involves conducting an in-depth analysis of area-wide standardized test results. With access to comprehensive data including math and reading scores of every student, as well as various school-related information, my objective is to synthesize this data to identify prominent trends in school performance.

The resultant report encompasses the following components:
   - District Summary
   - School Summary
   - Top 5 Performing Schools (By % Overall Passing)
   - Bottom 5 Performing Schools (By % Overall Passing)
   - Scores by Grade (9th to 12th)
   - Math scores
   - Reading scores
   - Scores by different categories
   - School Spending
   - School Size
   - School Type
   - Analysis

This analysis serves as a crucial foundation for informed decision-making and strategic planning within our educational framework.
________________________________________

## Analysis Report
________________________________________


### Local Government Area Summary

A comprehensive analysis was conducted to provide a succinct overview of key metrics within the local government area. Notably, the analysis encompassed math and reading scores of students, emphasizing a passing grade threshold of 50 or higher.


![image](https://github.com/Mago281/pandas-challenge/assets/131424690/13bf2d4e-35a2-4693-9f38-a671dd283a6b)

________________________________________
 
### School Summary

A detailed breakdown of each school's performance metrics was presented, shedding light on crucial aspects such as passing grades and overall performance:
<br>

$${\color{black}**Note:** \space \color{black}A  \space \color{blue}passing \space \color{blue}grade \space \color{black}is \space \color{blue}50 \space \color{black}or \space \color{blue}higher}$$ 
<p align="left">
</p>  

![image](https://github.com/Mago281/pandas-challenge/assets/131424690/b946ab5b-939b-4683-a811-db31e8747a4b)

________________________________________

### Highest 5 Performing Schools by Percentage of Overall Passing

The top 5 performing schools were identified based on the percentage of overall passing rates, providing insights into exemplary educational institutions:

![image](https://github.com/Mago281/pandas-challenge/assets/131424690/45653e1c-7282-49d8-9415-2e6cc4ec7c2d)

________________________________________

### Lowest 5 Performing Schools by Percentage of Overall Passing

Conversely, the bottom 5 performing schools were highlighted, emphasizing areas for improvement within the educational landscape:

![image](https://github.com/Mago281/pandas-challenge/assets/131424690/a3aaebf7-421c-4445-84cf-b26ab215cbcf)

________________________________________

### Scores by Grade (Grades 9 to 12)
________________________________________

### Math scores by Grade

An insightful breakdown of `average maths scores` across various grade levels `(year levels 9 to 12)` provided valuable insights into academic performance trends:

   <img src="https://github.com/Mago281/pandas-challenge/assets/131424690/973cb0f5-a537-4032-bda8-4b62caedb9bd" width="400" height="375">

________________________________________ 

### Reading scores by Grade

Similarly, the analysis extended to `average reading scores` across various grade levels `(year levels 9 to 12)`, contributing to a comprehensive understanding of educational dynamics.


   <img src="https://github.com/Mago281/pandas-challenge/assets/131424690/868e97d3-a39c-4376-8588-27de7648bf5e" width="400" height="375">

________________________________________

### Scores by School Spending

A detailed examination of school performance vis-a-vis average spending ranges per student revealed significant insights into the correlation between financial allocation and academic outcomes.

![image](https://github.com/Mago281/pandas-challenge/assets/131424690/ff203710-c690-4377-9af5-42647fded64c)
 
Implemented four bins with appropriate cutoff values to categorize school spending, thereby enhancing the organization of expenditure data:

Utilized the aforementioned scoring metrics to construct a meticulously structured DataFrame termed _`spending_summary`_

![image](https://github.com/Mago281/pandas-challenge/assets/131424690/7e213fd4-f47c-4a72-92ed-b2bf8b5b32fa)

________________________________________

### Scores by School Size

Stratifying school performance based on size categories facilitated a nuanced understanding of the impact of school size on academic achievements:

![image](https://github.com/Mago281/pandas-challenge/assets/131424690/4013aec4-4f87-4005-8723-36f7e819e62c)

Provided a DataFrame that broke down `school performance based on school size`:

![image](https://github.com/Mago281/pandas-challenge/assets/131424690/23d70d85-eddc-4b40-ad15-3a8a1618554a)

________________________________________

### Scores by School Type

The analysis also examined school performance concerning different types, providing insights into variations based on institutional characteristics:

![image](https://github.com/Mago281/pandas-challenge/assets/131424690/e632d31b-7c31-4864-b80e-d0ff89fc639e)

________________________________________
## Summary of Analysis
________________________________________

### Budget Allocation Impact:
My analysis revealed that funding levels did not consistently correlate with academic performance.  Lower per-student spending was associated with lower average scores and passing rates.

### School Size Matters:
Smaller schools tended to outperform larger ones, suggesting that smaller class sizes contributed to higher academic success.     

### School Type:
Independent schools, despite lower per-student budgets, exhibited higher overall performance compared to government schools, indicating potential efficiency differences between the two systems.
In particular, Independent schools performed 4.74% better in Maths and 2.66% better Reading. 

---

In conclusion, a targeted approach to budget allocation and class size management could enhance academic outcomes within the local government area. These findings underscore the importance of data-driven decision-making in shaping future educational initiatives.












