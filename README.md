# 📧 Flask Form Mailer

A simple and responsive Flask web application that allows users to submit a contact form, stores the submitted data in an SQLite database, and sends automated email notifications using SMTP.

---

## Features
- User-friendly contact form
- Stores form submissions in an SQLite database
- Sends email notifications automatically
- Server-side form validation
- Responsive and clean user interface
- Lightweight Flask backend


## Tech Stack
- Python
- Flask
- SQLite
- HTML5
- CSS3
- JavaScript
- SMTP (Email)


## 📂 Project Structure

```text
flask_formmailer/
│── app.py
│── database.db
│── requirements.txt
│── README.md
│── .gitignore
│── LICENSE
│
├── templates/
│   └── index.html
│
├── static/
│   ├── css/
│   ├── js/
│   └── images/
│
└── screenshots/
    ├── home.png
    ├── form.png
    ├── success.png
```


## Installation

### 1. Clone the repository
```bash
git clone https://github.com/prachipujarii-ai/flask_formmailer.git
```

### 2. Navigate to the project folder
```bash
cd flask_formmailer
```

### 3. Create a virtual environment (Recommended)
Windows
```bash
python -m venv venv
venv\Scripts\activate
```

macOS/Linux
```bash
python3 -m venv venv
source venv/bin/activate
```

### 4. Install dependencies
```bash
pip install -r requirements.txt
```

### 5. Configure Email Credentials
Update your email credentials inside the project (or preferably use environment variables).

Example:

```python
EMAIL_ADDRESS = "your_email@example.com"
EMAIL_PASSWORD = "your_app_password"
```


### 6. Run the application
```bash
python app.py
```

Open your browser and visit
```
http://127.0.0.1:5000
```


## Screenshots

### Form Interface:
<img width="862" height="911" alt="image" src="https://github.com/user-attachments/assets/8fab0755-63c8-4751-868b-b78259ae7719" />

### Information filled:
<img width="792" height="853" alt="Screenshot 2026-06-18 160642" src="https://github.com/user-attachments/assets/55b0f2e6-da26-41df-b2ff-6fb7357eae91" />

### Success Message:
<img width="986" height="930" alt="Screenshot 2026-06-02 003939" src="https://github.com/user-attachments/assets/2697fa84-6c42-417c-aba6-7b61f0bdd718" />

### Email Received:
<img width="870" height="420" alt="image" src="https://github.com/user-attachments/assets/8b7caaec-8eae-4935-bd53-4f1461682976" />

### Database table:
<img width="737" height="227" alt="image" src="https://github.com/user-attachments/assets/c0d1ae5a-d22c-42f2-b94d-1c1996644db6" />


## How It Works
1. User fills out the contact form.
2. Flask validates the submitted data.
3. Data is stored in the SQLite database.
4. An email notification is sent using SMTP.
5. A success message is displayed to the user.


## Future Improvements
- User authentication
- Admin dashboard
- File attachment support
- Better form validation
- PostgreSQL/MySQL integration
- REST API support
- Docker support
- Deploy on Render or Railway


## Requirements
- Python 3.10+
- Flask
- SQLite
- SMTP-enabled email account


Install all dependencies using:
```bash
pip install -r requirements.txt
```


## License

This project is licensed under the MIT License.


## Author

**Prachi Pujari**

GitHub  
https://github.com/prachipujarii-ai

LinkedIn  
https://www.linkedin.com/in/prachi-pujari-b77908312/
