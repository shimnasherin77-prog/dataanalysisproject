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

## Conclusion
Python and Excel marks are independent.

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

## Analysis
- Calculated total marks for each student
- Calculated average total marks per location
- Observation: The location with the highest average total marks is London,Tokoyo and New York.

# Student Count by Location

## Objective
Determine which location has the highest number of students in the dataset. This helps to understand the distribution of students across different cities.

## Dataset
Columns in the dataset:

- `student_id` – Unique student identifier
- `location` – City of the student
- `age` – Age of the student
- `sql_marks` – Marks in SQL
- `excel_marks` – Marks in Excel
- `python_marks` – Marks in Python
- `power_bi_marks` – Marks in Power BI
- `english_marks` – Marks in English

## Analysis
- Count the number of students per location
- Identify locations with the highest number of students
- Observation: The locations with the highest number of students are Tokyo and Los Angeles.

## Conclusion
Tokyo and Los Angeles have the largest student populations in the dataset.

# Lowest English Score by Location

## Objective
Identify which location’s student scored the lowest in English. This helps to understand areas where students may need extra support.

##  Dataset
Columns in the dataset:

- `student_id` – Unique student identifier
- `location` – City of the student
- `age` – Age of the student
- `sql_marks` – Marks in SQL
- `excel_marks` – Marks in Excel
- `python_marks` – Marks in Python
- `power_bi_marks` – Marks in Power BI
- `english_marks` – Marks in English

## Analysis
- We compared students’ English marks across all locations.
- The location with the lowest English score was identified.

## Conclusion
The student with the lowest English marks is from Berlin.

# Highest Excel Marks by Age Group

## Objective
Identify which age group achieved the highest marks in Excel. This helps to understand which age group performs best in this subject.

##  Dataset
Columns in the dataset:

- `student_id` – Unique student identifier
- `location` – City of the student
- `age` – Age of the student
- `sql_marks` – Marks in SQL
- `excel_marks` – Marks in Excel
- `python_marks` – Marks in Python
- `power_bi_marks` – Marks in Power BI
- `english_marks` – Marks in English

## Analysis
- The Excel marks of all students were compared across different age groups.
- The age group with the highest score was determined.

## Result
The 18-year-old age group achieved the highest mark in Excel.

## Conclusion
Students aged 18 excelled in Excel compared to other age groups.

The goal of this project is to analyze student performance across multiple subjects and locations to uncover patterns, strengths, and weaknesses. The insights can help educators make data-driven decisions for training, curriculum planning, and academic improvement.