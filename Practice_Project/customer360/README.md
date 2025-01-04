# Practice Project - Customer360

## Description
This project demonstrates the development of a Django application named *"Customer360"*. It consolidates customer communication records from various platforms into a central location. The project showcases essential Django concepts, including models, views, templates, and static files.

---

## Objectives
- Build a Django application to manage customer communication records.
- Understand and implement Django models, views, and templates.
- Capture and display customer interactions.
- Add additional functionalities to enhance the user experience.

---

## Features

### *Capture Communication Records*
- Record communication details such as channel, direction (inbound/outbound), and a summary.

### *Display Recent Interactions*
- Show customer interactions from the last 30 days.

### *Add New Customers*
- Create new customer records with fields like:
  - Name
  - Email
  - Phone
  - Address
  - Social Media (optional)

### *Manage Interactions*
- Record and manage customer interactions across channels:
  - Phone
  - SMS
  - Email
  - Letter
  - Social Media

### *Styling*
- Includes custom CSS for a visually appealing user experience.

---

## Models

### *Customer*
- id (Primary Key)
- name
- email
- phone
- address
- social_media (Optional)

### *Interaction*
- customer (Foreign Key to Customer)
- channel (Choices: phone, SMS, email, letter, social media)
- direction (Choices: inbound, outbound)
- interaction_date (Auto-added date)
- summary

---

## Setup Instructions

### *Prerequisites*
- Python 3.11 and pip must be installed on your system.

### *Installation*

1. *Clone the Repository*
   ```bash
   git clone git@github.com:afonseca00/IBM_Django_Application_Development_with_SQL_and_Databases.git
   cd customer360

2. *Create a virtual environment*
   ```bash
   python3 -m venv env
   source env/bin/activate # On Windows use `env\Scripts\activate`

3. *Install dependencies*
   ```bash
   pip install -r requirements.txt

4. *Apply migrations*
   ```bash
   python3 manage.py makemigrations
   python3 manage.py migrate

5. *Run the server*
   ```bash
   python3 manage.py runserver

6. *Access the application: Open your browser and navigate to*
   ```bash
   http://127.0.0.1:8000/
