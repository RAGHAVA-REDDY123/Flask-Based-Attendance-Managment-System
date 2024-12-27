# Flask-based-attendance-management-system

A simple web-based attendance management system built using Flask and Python. The system allows the management of student attendance, including marking attendance, viewing attendance reports, and managing the database.

# Features
User authentication.
Mark attendance for students.
View attendance reports.
Database integration to store attendance records.
Simple and intuitive web interface.
# Technologies Used
Python: Programming language for backend logic.

Flask: Web framework for building the web application.

HTML: Frontend technologies for the web interface.

# Installation

Follow these steps to run the project on your local machine.

# 1. Clone the repository
bash

Copy code

git clone https://github.com/yourusername/attendance-management-system.git

cd attendance-management-system
# 2. Create and activate a virtual environment

For Windows:

bash

Copy code

python -m venv venv

venv\Scripts\activate

# 3. Install the dependencies

bash

Copy code

pip install -r requirements.txt

# 4. Set up the database
The system uses SQLAlchemy to manage the database. To create the database, run the following command:

bash

Copy code

python manage.py db init  # Initialize the database

python manage.py db migrate  # Create migration files

python manage.py db upgrade  # Apply migrations and create the database

# 5. Run the Flask application

To start the Flask server, use the following command:

bash

Copy code

python app.py

By default, the application will be accessible at http://127.0.0.1:5000/.

# Usage

Upload:

Upload the images for the attendance verification.

Mark Attendance:

Admin or authorized users can mark attendance for students.

View Attendance:

Users can view a report of attendance by student and date.

Admin Features:

Admin can manage user roles, view attendance reports, and manage records.

# Contributions

Contributions are welcome! Feel free to fork the repository, make changes, and submit a pull request.


