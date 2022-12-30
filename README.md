# PyCitySchool

![metadata_image](https://user-images.githubusercontent.com/113273722/210090130-8582415b-d292-4bd9-ab01-cc775ea589f5.png)

# Background

My task is to analyze the district-wide standardized test results. that will help school board and mayor to make strategic decisions regarding future school budgets and priorities.

This datasets has tow csv format :

**1-** **schools_complete.csv file** : wich includes the following : ***Student ID***, ***school_name***, ***type***, ***size***, ***budget*** 

**2-** **students_complete.csv file** : which includes the followling : ***Student ID***, ***student_name*** ***,gender***,***grade***, ***school_name***, ***reading_score*** and ***math_score***. 

For these analysis both datasets imported, merged, and aggregate the data to showcase obvious trends in school performance.

***The final report includes the following :***

# 1-  District Summary 

A high-level snapshot of the district's key metrics in a DataFrame , Include the following:

-Total number of unique schools

**-** Total students

**-** Total budget

**-** Average math score

**-** Average reading score

**-** % passing math (the percentage of students who passed math)

**-** % passing reading (the percentage of students who passed reading)

**-** % overall passing (the percentage of students who passed math AND reading)

The district summery table looks as follows :
	
![Screenshot_20221230_120928](https://user-images.githubusercontent.com/113273722/210095731-fc7d8547-11e8-4946-96ce-4052599a16a8.png)

# School Summary

An overview table that summarizes key metrics about each school was created in the following metrics :

**-** School Name

**-** School Type

**-** Total Students

**-** Total School Budget

**-** Per Student Budget

**-** Average Math Score

**-** Average Reading Score

**-** % Passing Math (The percentage of students that passed math.)

**-** % Passing Reading (The percentage of students that passed reading.)

**-** % Overall Passing (The percentage of students that passed math and reading.)

The school summery table looks as follows:

![Screenshot_20221230_121538](https://user-images.githubusercontent.com/113273722/210096284-8b10c55f-e55a-4a68-9604-712f74449c1b.png)

# Top Performing Schools (By % Overall Passing)

The schools has been sorted by ***% Overall Passing*** in ***descending order*** and display the top 5 rows


![Screenshot_20221230_122005](https://user-images.githubusercontent.com/113273722/210096709-ef856f74-da22-4017-94ca-71aa4977b894.png)

# Lowest-Performing Schools (by % Overall Passing)

The schools has been sorted by ***% Overall Passing*** in ***ascending order*** and display the top 5 rows

![Screenshot_20221230_122603](https://user-images.githubusercontent.com/113273722/210097122-fe3f03f3-d14f-41fb-8c75-0174134f3d43.png)

# Math Scores by Grade

A DataFrame that lists the ***average math score*** for students of each grade level (9th, 10th, 11th, 12th) at each school

![Screenshot_20221230_122936](https://user-images.githubusercontent.com/113273722/210097384-331dc7fc-b048-4f48-a650-1b6c24a48a6a.png)

# Reading Scores by Grade

A DataFrame that lists the ***average reading score*** for students of each grade level (9th, 10th, 11th, 12th) at each school

![Screenshot_20221230_123139](https://user-images.githubusercontent.com/113273722/210097498-260b251d-a63e-4ff4-80e9-c2c01d5cfc91.png)

# Scores by School Spending

Atable that breaks down school performance based on ***average spending ranges (per student)***

The table includes the following:

Average Math Score

Average Reading Score

% Passing Math (The percentage of students that passed math.)

% Passing Reading (The percentage of students that passed reading.)

% Overall Passing (The percentage of students that passed math and reading.)

![Screenshot_20221230_123543](https://user-images.githubusercontent.com/113273722/210097798-387423a1-a2aa-4533-88e7-47c0169d44dd.png)

# Scores by School Size

A table that breaks down school performance based on school size (small, medium, or large)

![Screenshot_20221230_123815](https://user-images.githubusercontent.com/113273722/210098001-52b16d54-5064-44ad-b76d-060fea3ccb53.png)


# Scores by School Type

A table that breaks down school performance based on type of school (district or charter)

![Screenshot_20221230_124001](https://user-images.githubusercontent.com/113273722/210098165-2cbd2d73-8bc5-4bb3-91a1-25c084217653.png)

# Analysis and observable Trends

***1_*** The ***district summary dataset*** has a total of 15 schools and 39,170 students.

The total students average reading score is 81.87 which is higher than the average math score 78.98.

and passing rate reading (85.80%) has a higher rate than math (74.98 % ), These findings indicate that student's are doing better in reading than math.

***2-*** The school summary shows that from the 15 schools, (7 District Schools and 8 Charter Schools)

The district schools have more students than the charter schools, which can mean that

the district schools’ geographical coverage can be a reason for their larger student population/size.

***3_*** From Highest-Performing Schools(by % Overall Passing) and Lowest-Performing Schools(by % Overall Passing) tables shows that 
the charter schools is performing better than the destrict schools and this may that the charter schools has less students that the district schools

***-4*** Based on the performance of spending ranges per student, 
students have a higher overall passing rate of 90.37 percent in the lower spending ranges (<$585)

***5_*** The data shows that the Charter Schools are scoring better than the District Schools across all metrics (average, percent, and overall).

Pena High School has the average math score (83.839917) with (94.59%) passing math and average reading score (84.044699) with (95.94%) passing reading

while Huang High School has the average math score (76.629414) with (65.68%) passing math and average reading score (81.182722) with (81.31%) passing reading.

Since Pena High School is a charter school with better scores and smaller student population while Huang High School is a district school with lower scores and larger student population,

***Finally*** :

small and medium sized schools performed better than large sized schools, so schools with larger student population/ size negatively influences student achievements.





