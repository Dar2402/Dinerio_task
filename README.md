# Employee Management System

This is a minimal Employee Management System built with Django. The system consists of three main modules:

1. **Employee Management:** Allows for the addition, updating, and deletion of employees. Each employee has attributes such as Name, Email, Address, Designation, Reporting Manager, and Department.

2. **Department Management:** Provides functionality to manage departments, including adding, updating, and deleting departments. Each department has attributes like Name and Floor.

3. **Employee Salary Management:** Manages employee salaries over time. Allows for adding, updating, and deleting salary entries with specified date ranges.

## Features

### Employee Management Module

- **Admin Page:** Allows administrators to add, update, and delete employee records.
- **Reporting Hierarchy Page:** Displays the reporting hierarchy within each department, showing who reports to whom.

### Department Management Module

- **Admin Page:** Enables administrators to add, update, and delete department records.
- **Reporting Hierarchy Page:** Displays the reporting hierarchy within each department, with managers at the top and multiple TLs and associates below.

### Employee Salary Management Module

- **Admin Page:** Allows administrators to add, update, and delete salary entries with specified date ranges.
- **Department-wise Salary Report Page:** Enables the viewing of department-wise salary costs within a specified date range.

## Tech Stack

- **Python:** The primary programming language.
- **Django:** The web framework used for building the application.
- **Database:** Can be MySQL, or any other preferred database.
- **Frontend:** Utilizes JavaScript for interactive features.

## Setup Instructions

1. Clone the repository to your local machine.
2. Install the required libraries using pip install -r requirements.txt.
3. Configure the database settings in the settings.py file.
4. Run migrations using python manage.py migrate.
5. Create a superuser for the Django admin using python manage.py createsuperuser.
6. Run the development server with python manage.py runserver.
7. Access the Django admin at http://localhost:8000/admin/ and login with the superuser credentials.

## Project Structure

- *darshan_employee_management_system/:* The main Django project folder.
  - *employee/:* The Django app for the Employee Management System.
    - *models.py:* Contains the database models for employees, departments, and salary entries.
    - *views.py:* Handles the logic for rendering views.
    - *admin.py:* Customizes the Django admin interface.
    - *templates/:* Contains HTML templates for rendering views.
    - *static/:* Stores static files such as CSS and JavaScript.




For any clarifications or assistance, please reach out to Darshan Pandey at darshanrpandey243@gmail.com 
