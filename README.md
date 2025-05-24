# E-Learning Platform

This is a simple E-Learning web application built with Flask and SQLite. It supports user registration and login for students and faculty, course and assignment management, assignment submissions, and feedback.

## Features

- User registration and login (Student/Faculty roles)
- Faculty can create courses and assignments
- Students can view courses and assignments
- Students can submit assignment answers
- Faculty can view submissions and provide grades/feedback

## Project Structure

```
app.py
elearning.db
s.py
templates/
    assignments.html
    create_assignment.html
    create_course.html
    faculty_dashboard.html
    home.html
    login.html
    provide_feedback.html
    register.html
    student_dashboard.html
    submissions.html
    submit_assignment.html
    view_assignments.html
    view_courses.html
    view_submissions.html
```

## Getting Started

### Prerequisites

- Python 3.x
- Flask (`pip install flask`)

### Setup

1. Clone the repository.
2. Install Flask:
    ```sh
    pip install flask
    ```
3. Run the application:
    ```sh
    python app.py
    ```
4. Open your browser and go to [http://127.0.0.1:5000](http://127.0.0.1:5000)

The database (`elearning.db`) will be created automatically on first run.

## Usage

- Register as a student or faculty.
- Faculty can create courses and assignments.
- Students can view courses, assignments, and submit answers.
- Faculty can view submissions and provide feedback.
