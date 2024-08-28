Fitness Wellness Platform
Welcome to the Fitness Wellness Platform – a web application that empowers individuals to achieve their fitness goals, track progress, and connect with a supportive community of like-minded individuals.


Project Overview
The Fitness Wellness Platform is designed to provide users with an easy-to-use interface for managing their fitness routines, monitoring their progress, and interacting with a community. This platform offers a responsive design, ensuring a seamless experience across both web and mobile devices.

Features
User Registration and Authentication: Users can sign up, log in, and securely manage their accounts.
Progress Tracking: Track fitness goals, workouts, and overall progress.
Community Interaction: Engage with other users and share progress.
Responsive Design: Accessible on both web and mobile platforms.
Tech Stack
Backend: Python, Flask
Database: SQLite
Frontend: HTML, CSS, JavaScript
Deployment: Heroku
Setup Instructions
Prerequisites
Python 3.x
pip (Python package manager)


Installation
Clone the repository:



git clone https://github.com/your-username/fitness-wellness-platform.git
cd fitness-wellness-platform
Set up a virtual environment:


python3 -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
Install dependencies:


pip install -r requirements.txt
Set up the SQLite database:


flask db init
flask db migrate -m "Initial migration."
flask db upgrade
Running the App
Start the Flask development server:


python run.py
Access the application in your browser:


http://localhost:5000
Deployment
To deploy the app on Heroku:

Login to Heroku:


heroku login
Create a new Heroku app:


heroku create your-app-name
Deploy the app:


git push heroku master
Open the app in your browser:


heroku open
License
This project is licensed under the MIT License. See the LICENSE file for details.
Author:- Mohammad Ammar


