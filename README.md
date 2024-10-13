# Student Performance Tracker

## Overview
The Student Performance Tracker is a web application built with Flask that allows teachers to manage student information and track their grades. Users can add students, view their details, add grades for subjects, and calculate the class average. This project is designed to help educators effectively monitor and improve student performance.

## Features
- **Add New Students**: Input the name and roll number of new students.
- **Add Grades**: Assign grades for specific subjects to each student.
- **View Student Details**: Access detailed information about each student, including their grades.
- **Calculate Class Average**: Compute and display the average grade for all students in the class.

## Technologies Used
- **Python**: The primary programming language used in the project.
- **Flask**: The web framework used to build the application.
- **HTML/CSS**: For front-end user interface design.
- **JavaScript**: For client-side validation and interactivity.
- **JSON**: For storing student data.

## Directory Structure
student-performance-tracker/ ├── app.py # Main Flask application file ├── student_tracker.py # Module that manages student data ├── requirements.txt # Dependencies for the project ├── static/ # Static files (CSS, JavaScript) │ ├── style.css # CSS stylesheet │ └── script.js # JavaScript file └── templates/ # HTML templates ├── index.html # Home page template ├── add_student.html # Template for adding a new student ├── add_grade.html # Template for adding a grade to a student ├── view_students.html # Template for viewing all students ├── view_student.html # Template for viewing a specific student's details └── class_average.html # Template for displaying class average
