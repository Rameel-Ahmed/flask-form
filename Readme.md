# 📝 Job Application Form – Flask App

This is a simple Flask web application that allows users to submit a job application form. The submitted data is:

- Stored in a SQLite database
- Emailed to the user using Gmail
- Displayed with a success message on the frontend

---

## 🚀 Features

- User-friendly form with Bootstrap styling
- Stores submissions (first name, last name, email, start date, occupation)
- Sends a confirmation email to the user's email address
- Uses SQLite as the backend database
- Uses Flask-Mail to send emails

---

## 🛠️ Technologies Used

- Python 3
- Flask
- Flask-Mail
- Flask-SQLAlchemy
- Bootstrap 5 (for frontend styling)
- SQLite (as the database)

---

## 📋 How It Works

### 🧑 User Flow

1. User opens the form (GET request).
2. User fills in:
   - First Name
   - Last Name
   - Email
   - Available Start Date
   - Occupation (radio button)
3. User submits the form (POST request).
4. The app:
   - Saves data to the SQLite database
   - Sends a confirmation email to the user
   - Flashes a success message on the same page

---

## ⚙️ Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/Rameel-Ahmed/flask-form.git
   cd flask-form
