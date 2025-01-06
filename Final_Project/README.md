# Final Project - Online Course Application

## Description

This is the final project for the Django Application Development with SQL and Databases course. The goal of this project is to build an online course application that allows users to enroll in courses, view lessons, and take exams.

## Features

- User registration and authentication
- Course and lesson management
- Exam with multiple-choice questions
- Exam submission evaluation
- Display of exam results

## Technologies Used

- Django
- SQLite
- Bootstrap

## Setup Instructions

1. Clone the repository:
    ```sh
    git clone https://github.com/afonseca00/IBM_Django_Application_Development_with_SQL_and_Databases.git
    cd IBM_Django_Application_Development_with_SQL_and_Databases/Final_Project
    ```

2. Create and activate a virtual environment:
    ```sh
    python3 -m venv djangoenv
    source djangoenv/bin/activate  # On Windows use: djangoenv\Scripts\activate
    ```

3. Install the dependencies:
    ```sh
    pip install -r requirements.txt
    ```

4. Run the migrations:
    ```sh
    python3 manage.py makemigrations
    python3 manage.py migrate
    ```

5. Create a superuser:
    ```sh
    python3 manage.py createsuperuser
    ```

6. Start the development server:
    ```sh
    python3 manage.py runserver
    ```

7. Access the application in your browser:
    ```
    http://127.0.0.1:8000/
    ```

## Testing

To test the application, follow these steps:

1. Log in to the admin panel:
    ```
    http://127.0.0.1:8000/admin/
    ```

2. Create a course, lessons, and exam questions using the admin panel.

3. Access the course page and take an exam.

4. Check the exam results on the results page.

## Project Structure

```markdown
IBM_Django_Application_Development_with_SQL_and_Databases/
├── Final_Project/
│   ├── myproject/
│   │   ├── settings.py
│   │   ├── urls.py
│   │   ├── wsgi.py
│   │   └── ...
│   ├── onlinecourse/
│   │   ├── models.py
│   │   ├── views.py
│   │   ├── admin.py
│   │   ├── templates/
│   │   │   ├── onlinecourse/
│   │   │   │   ├── course_details_bootstrap.html
│   │   │   │   ├── exam_result_bootstrap.html
│   │   │   │   └── ...
│   │   └── ...
│   ├── manage.py
│   ├── requirements.txt
│   └── ...
