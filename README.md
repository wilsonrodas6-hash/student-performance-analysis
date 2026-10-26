# Student Performance Analysis (R)

Exploratory data analysis of student performance in a secondary-school math course, using R, tidyverse, and ggplot2.

## Questions
1. How strongly do earlier grades predict the final grade?
2. Which factors (study time, absences, past failures, and others) are linked to final grades?
3. Do students who plan to pursue higher education perform differently?

## Key findings
- Second-period grades are very strong predictors of final grades (correlation 0.97).
- Past class failures (-0.29) and absences (-0.21) show the strongest links to lower final grades among background factors.
- Students planning higher education scored about 2 points higher on average (small comparison group of 14).

## Process
Import and inspect, clean (no missing values or duplicates; 38 students with a final grade of 0 excluded), analyze, visualize, and report.

## Files
- `analysis.Rmd`: full analysis and report (R Markdown)
- `analysis.html`: knitted report
- `data/student-mat.csv`: dataset

## Data source
Student Performance dataset, UCI Machine Learning Repository (Cortez & Silva, 2008).

## Tools
R, tidyverse, janitor, skimr, ggplot2, R Markdown
