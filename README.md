# pandas-challenge
In this "Pandas Challenge", I aimed to provide a comprehensive analysis of school district data using the Python Pandas library. This project systematically calculates and organizes key educational components, offering insights into school performance. The analysis covers aspects such as overall district performance, individual school summaries, top and bottom-performing schools, grade-level scores, and the impact of factors like spending, size, and school type on academic outcomes. This project serves as a practical way to showcase data manipulation, exploration, and presentation skills using Pandas, contributing valuable insights for informed decision-making in education, empirically speaking.

District Summary:
Perform calculations and create a high-level snapshot of the district's key metrics in a DataFrame:

Total number of unique schools, total students, total budget, average math score, average reading score, % passing math, % passing reading, % overall passing.

School Summary:
Perform calculations and create a DataFrame summarizing key metrics about each school:

School name, school type, total students, total school budget, per student budget, average math score, average reading score, % passing math, % passing reading, % overall passing.

Highest-Performing Schools:
Sort schools by % Overall Passing in descending order, display the top 5 rows. Save as "top_schools".

Lowest-Performing Schools:
Sort schools by % Overall Passing in ascending order, display the top 5 rows. Save as "bottom_schools".

Math Scores by Grade:
Create a DataFrame listing average math score for each grade level (9th-12th) at each school.

Reading Scores by Grade:
Create a DataFrame listing average reading score for each grade level (9th-12th) at each school.

Scores by School Spending:
Break down school performance based on average spending ranges (per student):

Spending bins: [0, 585, 630, 645, 680], Labels: ["<$585", "$585-630", "$630-645", "$645-680"].

Use pd.cut for categorization, calculate mean scores per spending range, and create "spending_summary" DataFrame.

Metrics in the table: Average math score, average reading score, % passing math, % passing reading, % overall passing.

Scores by School Size:
Bin the per_school_summary based on total students:

Size bins: [0, 1000, 2000, 5000], Labels: ["Small (<1000)", "Medium (1000-2000)", "Large (2000-5000)"].

Create "size_summary" DataFrame to show school performance based on size.

Scores by School Type:
Use the per_school_summary DataFrame to create "type_summary" showing school performance based on "School Type".

Analysis: 
In order to complement my work and provide additional insight into this project, there are a few important conclusions we can draw from the data. When looking at school size and the impact on performance, 
we can observe that smaller and medium-sized schools tend to have higher average math and reading scores as well as higher passing rates compared to larger schools. This can suggest that academic performance
may be influenced by school size. When looking at spending per student, it is observed that schools with lower per student budget appear to achieve higher average scores and passing rates which implies that efficient resource allocation may positively impact academic outcomes. For grade level performance, it is revealed that the math and reading scores by grade reveal trends in academic performance which can highlight areas that may need improvement. Finally, when looking at school type, we can discern that on average, charter schools tend to have higher average scores and passing rates in both math and reading compared to district schools which suggests that school type might be a significant factor in acadmeic success.
