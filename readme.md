# Student Marks Analysis

## Description
This project analyzes student exam data and provides visual insights using Python.  
It uses **Seaborn** and **Matplotlib** to generate plots such as barplots, histograms, and heatmaps to compare student scores across different subjects and locations.

## Dataset
The dataset contains the following fields:
- `student_id` – Unique identifier for each student
- `location` – Student’s location
- `age` – Student’s age
- `sql_marks`, `excel_marks`, `python_marks`, `power_bi_marks`, `english_marks` – Marks obtained in different subjects

## Features
- Visualize individual subject scores by location or age
- Compare marks between subjects (e.g., Python vs Excel)
- Generate correlation heatmaps to find relationships between subjects
- Identify top and low-performing students

# Python vs Excel Marks Analysis

## Objective
Visualize students Python marks in comparison to their Excel marks using a bar chart.

## Dataset
Columns in the dataset:
- student_id – Unique student identifier
- location – City of the student
- age – Age of the student
- sql_marks – Marks in SQL
- excel_marks – Marks in Excel
- python_marks – Marks in Python
- power_bi_marks – Marks in Power BI
- english_marks – Marks in English

## Analysis
- A bar chart was created to compare Python marks across students grouped by their Excel marks.
- Observation: There is no dependency between Python and Excel marks. Students’ performance in one subject does not predict performance in the other.

# Conclusion
- Python and Excel marks are independent.

# Location-wise Average Total Marks Analysis
## Objective
Identify which location has the highest average total marks across all exams for students.
This helps to understand which city’s students performed best overall in all subjects.

## Dataset
Columns in the dataset:
- student_id – Unique student identifier
- location – City of the student
- age – Age of the student
- sql_marks – Marks in SQL
- excel_marks – Marks in Excel
- python_marks – Marks in Python
- power_bi_marks – Marks in Power BI
- english_marks – Marks in English

# Analysis
Calculated total marks for each student:
~~~ data['total_marks'] = data[['sql_marks', 'excel_marks', 'python_marks', 'power_bi_marks', 'english_marks']].sum(axis=1) ~~~

Calculated average total marks per location:
~~~ avg_marks_location = data.groupby('location')['total_marks'].mean().reset_index() ~~~

Observation: The location with the highest average total marks is London,Tokoyo and New York.

