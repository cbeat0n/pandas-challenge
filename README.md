# pandas-challenge
This is the public repository for the Module 4 Homework in the UofM Data Analysis Bootcamp

Summary Analysis:
This data analysis file (.ipynb) contains the following analysis:
- One Dataframe containing District wide summary statistics such as the number of schools, number of students, total budget,
average math and average reading scores, % passing math, % passing reading, and % overall passing scores.
- One Dataframe containing a summary of the district based on the school, with statistics including the school type, number of students, 
total school budget, budget per capita, average math and reading scores, % passing math, % passing reading, and % overall passing scores.
- Two Dataframes that were taken from the above mentioned Dataframe and sorted by the % overall passing scores. One is the top 5 schools with the highest passing rates, and the bottom 5 schools with the lowest % passing rates.
- Two Dataframes which hold the average math/reading scores for the school and grade, row and column respectively.
- Three Dataframes which hold the averagea math/reading scores, % passing math, % passing reading, and % overall passing when
grouped by different bins for the following categories: Spending per Student, School Size, and School Type.
- Other code inbetween each of the nine aforementioned dataframes to come to the conclusions found below, such as the sb_budget
DataFrame


Two Data Conclusions:
Two conclusions can be drawn from the data when looking at the sb_budget dataframe, which is the per_school_summary sorted by Total School Budget. 
- Charter schools are smaller than District schools, as seen by School Type vs Total Students. There is a complete separation of type that is very clean and akin to a pd.cut().
- There is a positive linear relationship between the two increasing columns Total Students and Total School Budget.

Some additional conclusions that can be drawn:
- In the Spending Ranges per Student Groupby Dataframe, there is a negative correlation between average math, reading scores as well 
as % passing scores. Ergo, the more money spent per student the less people are passing or the lower the average score.
- In the School Size Groupby Data Frame, there is a negative correlation between school size and average math and reading scores. Ergo,
the bigger the school the lower the average math and reading scores.
