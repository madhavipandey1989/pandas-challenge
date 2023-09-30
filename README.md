# pandas-challenge

Project expores the possibilities pandas library provides for data analysis. 
- PyCitySchools\PyCitySchools_starter.ipynb has the analysis scripted, described below.
- PyCitySchools\Resources\schools_complete.csv and PyCitySchools\Resources\students_complete.csv provides the raw data for the analysis.
- ANalysis report is captured in this readme below, in PyCitySchools_starter.ipynb as well as in "Pandas Challange Project report.docx" in repository.


# PyCity Schols Analysis
In this project we were given 2 different datasets,

Schools data, which explains the schol name, ID, Budget, school type(Dstrict vs Chartered), and school size(number of students). Stored in the file named schools_complete.csv
Student data, which records per student data for student ID, Student name, gender, grade, school name, math score, reading score.
We joined the data of both records in data frame, and calculated District summary where we calculated school count, student count, total budget, average math score, average reading score, passing math percentage, passing reading percentage and overall passing rate. We also calculated school summary, where we calculated school types, per school studen count, per school budget and capita, average test score, no of students per school math score greater than 70, no of students per school reading score greater than 70, no of students per school that passed both maths and reading greaterthan 70, overall passing rates.

We also calculated %Overall Passing and found top schools and bottom schools. We also calculated the math and reading scores by grade per school. We analyzed at the school score by spending summary per capita, based on size of the school and school types.

We analyzed the combined data of student results and school data, where we collected following conclusions,

Small and medium size schools had better overall passing scores than large schools
Schools which have smaller per capita budget (between 585 to 630), had better overall passing scores than schools having higher per capita budget.
Looking at school types, we could observe that Chartered schools had better overall passing scores than District schools.
This is also observered that the maths scores have bigger variations between schools types, means students going to chartered schools were scoring better in maths than students going to District schools.
