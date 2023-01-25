## Background and Context

This project utilizes Pandas to bring both high-level and acute analyses and summaries of the city's school district data. This analysis will aid the school board in making data-driven decisions and in coming to conclusions about budget, spending, and how to better allocate resources based on the needs of the district.

The two datasets used for analysis are csv files titled [schools_complete.csv](https://github.com/emilyneaville/pandas-challenge/blob/main/PyCitySchools/Resources/schools_complete.csv) includes key information about the each school in the district such as 'School ID', 'school_name', 'type', 'size', and 'budget'. [students_complete.csv](https://github.com/emilyneaville/pandas-challenge/blob/main/PyCitySchools/Resources/students_complete.csv) includes key information about the each school in the district such as 'Student ID', 'student_name', 'gender', 'grade', 'school_name', 'reading_score', and 'math_score'. These datasets are merged at the beginning of analysis to ensure accurate analysis and aggregation of data for the DataFrames created.

## Trends, analyses, and observations

#### Sub-par overall passing percentage
- Looking at the District Summary, it is immediately noticeable that the overall percentage of students that passed both math and reading is sub-par at just 65.17%. This prompts further investigation on what is creating this low statistic, and in the Per School Summary we can see why: 7 of the 15 schools in the district have an overall passing percentage of lower than 55%. 
    - Why do these 7 schools have such low scores? The answer may be found by examining the school type. These 7 schools are district schools, which historically underperform when compared to charter schools. This observation can be further solified by comparing the Top 5 Performing Schools, the Bottom 5 performing schools, and the math and reading Scores by School Type.
    - District schools underperform in both math and reading compared to charter schools, however the greatest discrepency is in math. The average math score for charter schools is about an 83 while the average math score for district schools is around 76.
    - My one recommendation to the school board in this regard would be to investigate further into their math department and operations. Some qualitative research could be done by comparing curriculum and comparing staff, for example. 

#### Scores by Spending per Student
- When analyzing the math and reading scores by School Spending ranges per student, there is an very insteresting observable trend. According to the summary table, the more a school spends per student, the lower the average math and reading scores are. This prompts multiple questions that would either require additional investigation by the school board or additional data:
    - Why are average scores lowering when schools spend more on students? What is that extra funding going toward, that is, what is the difference between spending habits of lower-funded schools vs. higher-funded schools? Is the funding going toward things such as administrative costs, extracurricular activities, or operational costs?
    - These are the questions I suggest the school board ask themselves in order to get clearer insight on this discrepency.