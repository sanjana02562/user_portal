# 🏥 User Portal – Django Web App

A role-based user management system built with **Django**, featuring **Custom User Authentication** and separate dashboards for Patients and Doctors.

---

## ✨ Features
- **Custom User Model** with additional fields (address, pincode, profile picture, etc.)
- **Role-based Dashboards**:
  - 🧍 **Patient Dashboard**
  - 👨‍⚕️ **Doctor Dashboard**
- **Responsive Bootstrap UI**
- User profile picture upload
- Login, Signup, and Logout functionality
- Redirection based on user type
- Home button for easy navigation

---

## 📂 Tech Stack
- **Backend**: Django 5, Python 3.12
- **Frontend**: HTML, CSS, Bootstrap
- **Database**: SQLite (default, can be changed)
- **Version Control**: Git & GitHub

---


## 🚀 Setup Instructions
1. Clone the repository:
   git clone https://github.com/your-username/your-repo.git

2. Navigate to the project directory:
   cd user_portal

3. Create and activate a virtual environment:
   python -m venv venv
   venv\Scripts\activate   # On Windows
   source venv/bin/activate  #Mac/Linux

4. Install dependencies:
   pip install -r requirements.txt

5. Apply migrations:
   python manage.py migrate

6. Run the development server:
   python manage.py runserver

---

## 🛠 Future Improvements

Email verification during signup

Password reset via email

Admin dashboard for managing users

