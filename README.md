## Background and Context

This project utilizes Pandas to bring both high-level and acute analyses and summaries of the city's school district data. This analysis will aid the school board in making data-driven decisions and in coming to conclusions about budget, spending, and how to better allocate resources based on the needs of the district.

The two datasets used for analysis are csv files titled [schools_complete.csv](https://github.com/emilyneaville/pandas-challenge/blob/main/PyCitySchools/Resources/schools_complete.csv) includes key information about the each school in the district such as 'School ID', 'school_name', 'type', 'size', and 'budget'. [students_complete.csv](https://github.com/emilyneaville/pandas-challenge/blob/main/PyCitySchools/Resources/students_complete.csv) includes key information about the each school in the district such as 'Student ID', 'student_name', 'gender', 'grade', 'school_name', 'reading_score', and 'math_score'. These datasets are merged at the beginning of analysis to ensure accurate analysis and aggregation of data for the DataFrames created.

## Trends, analyses, and observations

#### Sub-par overall passing percentage
- Looking at the District Summary, it is immediately noticeable that the overall percentage of students that passed both math and reading is sub-par at just 65.17%. This prompts further investigation on what is creating this low statistic, and in the Per School Summary we can see why: 7 of the 15 schools in the district have an overall passing percentage of lower than 55%. 
    - 