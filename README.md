# IBM Django Application Development with SQL and Databases

## Description

This repository contains two main projects completed as part of the IBM Django Application Development with SQL and Databases course. These projects are designed to demonstrate the use of Django, SQL, and database management in creating web applications.

## Projects

### 1. Practice Project

#### Description

The Practice Project is a preliminary project aimed at familiarizing with Django's core features and functionalities. This project covers basic operations such as creating models, views, templates, and configuring URLs.

#### Features

- User authentication
- Basic CRUD operations
- Simple form handling
- Basic template rendering

#### Setup Instructions

1. Clone the repository:
    ```sh
    git clone https://github.com/afonseca00/IBM_Django_Application_Development_with_SQL_and_Databases.git
    cd IBM_Django_Application_Development_with_SQL_and_Databases/Practice_Project
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

### 2. Final Project - Online Course Application

#### Description

The Final Project is a comprehensive application that allows users to enroll in courses, view lessons, and take exams. It demonstrates advanced features such as user authentication, course management, and exam evaluation.

#### Features

- User registration and authentication
- Course and lesson management
- Exam with multiple-choice questions
- Exam submission evaluation
- Display of exam results

#### Setup Instructions

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
