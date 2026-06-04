## Project Overview
This is a Flask web application that:
- Accepts user form submissions (name, email, date, occupation)
- Stores the data in a SQLite database
- Sends a confirmation email to the user via Gmail SMTP
- Displays a success message on the frontend

Built with:
- Flask
- Flask-SQLAlchemy
- Flask-Mail
- SQLite

## Setup & Run Instructions
1. Clone the repository:
   git clone ```https://github.com/your-username/flask-formmailer.git```
   cd flask-formmailer

2. Install dependencies:
   ```pip install -r requirements.txt```

3. Create a .env file with your secrets:
   SECRET_KEY=your_secret_key
   MAIL_USERNAME=your_email@gmail.com
   MAIL_PASSWORD=your_app_password

4. Run the app:
   ```flask run```
   or
   ```python app.py```


<img width="971" height="965" alt="image" src="https://github.com/user-attachments/assets/52664291-e43e-4592-8e43-72431c2f2648" />

## Features
- Form submission with validation
- SQLite database storage
- Email notifications via Gmail SMTP
- Flash messages for user feedback
