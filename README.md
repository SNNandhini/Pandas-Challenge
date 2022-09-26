# Pandas-Challenge
Homework: Pandas, Pandas, Pandas

## School and Standardized Test Data Analysis
The data provided for this analysis are present in two files. One containing the school data (school name, type, number of students and budget) and the other containing students details (student name, gender, grade, school, Math and Reading scores). The data from both the files are combined into one DataFrame using Pandas for analysis.

### Pandas Script and Results
1.  The Pandas script developed for this assignment along with the results, can be found in Pandas-Challenge/PyCitySchools/PyCitySchools.ipynb
2.  The Source data used can be found in the files Pandas-Challenge/PyCitySchools/Resources/schools_complete.csv and Pandas-Challenge/PyCitySchools/Resources/students_complete.csv
3.  The script in the Jupyter Notebook does the following:
    -   The data from the source files are read into the DataFrames school_data and student_data.
    -   The DataFrames above are merged into one dataset school_data_complete. This merged DataFrame is used for all calculations.
    -   District Summary: The values required are calculated and stored in the DataFrame dist_summary.
    -   School Summary: The values required are calculated and grouped by schools which are then stored in the DataFrame school_summary.
    -   Highest-Performing Schools (by % Overall Passing): The school_summary dataframe is sorted by % Overall Passing to display the top 5 performing schools.
    -   Lowest-Performing Schools (by % Overall Passing): The school_summary dataframe is sorted by % Overall Passing to display the bottom 5 performing schools.
    -   Math Scores by Grade: The Math scores of the students are filtered by Grade (9th, 10th, 11th and 12th) and grouped by School. This is then sored in the DataFrame math_grade_summary.
    -   Reading Scores by Grade: The Reading scores of the students are filtered by Grade (9th, 10th, 11th and 12th) and grouped by School. This is then sored in the DataFrame reading_grade_summary.
    -   Scores by School Spending: The data is sliced and binned based on the Per Data Budget. The school_summary dataframe is updated with a new column for the bins. The data from the school_summary is then grouped by the bins created into the DataFrame school_spending_score.
    -   Scores by School Size: The data is sliced and binned based on the Number of Students. The school_summary dataframe is updated with a new column for the bins. The data from the school_summary is then grouped by the bins created into the DataFrame school_size_score.
    -   Scores by School Type: The school_summary dataframe is grouped by School Type and the resuts stored in DataFrame school_type_score.
4.  The conclusions based on the above analysis are available both on the above Jupyter Notebook and the word document Pandas-Challenge/School_Performance_Report.docx

### Files Submitted
1.  Jupyter Notebook - Pandas-Challenge/PyCitySchools/PyCitySchools.ipynb
2.  Source Data - Pandas-Challenge/PyCitySchools/Resources/schools_complete.csv and Pandas-Challenge/PyCitySchools/Resources/students_complete.csv
3.  Written Report - Pandas-Challenge/School_Performance_Report.docx