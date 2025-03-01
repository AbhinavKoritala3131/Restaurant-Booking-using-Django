# Restaurant-Reservation-using-Django

A simple Django-based application for managing restaurant reservations, displaying the menu, and allowing customers to book a table online. This project is part of a learning exercise from the Meta Certification course.

#Features
Home Page: Welcome page of the restaurant.
About Page: Information about the restaurant.
Booking System: Users can make reservations by filling out a booking form.
Menu: Displays a list of available menu items.
Menu Details: Displays individual menu item details when selected.

#Installation
To run this project locally, follow these steps:

Step 1: Set up a Virtual Environment
Create and activate a virtual environment:


python -m venv venv
For Windows:


venv\Scripts\activate
For macOS/Linux:


source venv/bin/activate
Step 2: Install Dependencies
Once the virtual environment is activated, install the required dependencies using pip:


pip install django mysqlclient
Step 3: Set up the Database
Make sure you have MySQL installed. Then, configure the database connection in settings.py (adjust the credentials to match your MySQL setup).

Run the following commands to apply migrations and set up the database:


python manage.py migrate
Step 4: Run the Development Server
Start the Django development server:


python manage.py runserver
You can now access the application by visiting http://127.0.0.1:8000 in your web browser.

#Usage
Home Page: Displays the homepage with a simple welcome message.
About Page: Displays information about the restaurant.
Book a Table: Navigate to the booking page and fill out the form to make a reservation.
Menu: View the list of menu items and select an item for more details.

#Dependencies
Django: A Python web framework used to build the application.
mysqlclient: MySQL database connector for Django.
Python: The programming language used to develop the application.

#Author
This project was an individual project created during the Meta Certification course as part of a learning exercise.

#License
This project is open-source. Feel free to use and modify it as you wish.
