# PyCitySchools

The first cell imports modules we will need, makes paths to the separate csv files that will be used, reads the csv files, and merges them together.

The second cell will use the merged csv file to create a summary table of the school district. 

Calculate the total number of schools,
Calculate the total number of students,
Calculate the total budget,
Calculate the average math score,
Calculate the average reading score,
Calculate the percentage of students with a passing math score (70 or greater),
Calculate the percentage of students with a passing reading score (70 or greater),
Calculate the percentage of students who passed math and reading (% Overall Passing).

The next cell is a bit more complicated, as we will need to start using .groupby() quite frequently to pull data from the merged dataframe to find values for individual schools, instead of summing up values for the entire district. This cell will create an overview table showing the following info for each school: 

School Name
School Type
Total Students
Total School Budget
Per Student Budget
Average Math Score
Average Reading Score
% Passing Math
% Passing Reading
% Overall Passing (The percentage of students that passed math and reading.)

The next two make tables for the best and worst performing schools, after which two tables are made that show average reading and math levels for each school broken down by grade. This is mainly done with the use of .groupby() and .mean().

The final section of the project shows several statistics about the districts by creating pandas bins and dataframes. Average math score, average reading score, passing rate for math/reading, and average passing rate of both math and reading combined are laid out. These stats are sorted according to how much each school spends per student, school size, and school type (charter or district).
