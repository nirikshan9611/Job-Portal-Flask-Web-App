# 💼 Job Portal Web Application

A full-stack Job Portal built with Python and Flask. Supports three user roles — Job Seeker, Employer, and Admin — with live job listings from external APIs.

---

## 🚀 Features

- 🔐 User registration and login with role selection (Job Seeker / Employer / Admin)
- 🌐 Live job listings fetched from **Remotive** and **Arbeitnow** external APIs
- 🔍 Search jobs by keyword, location, and category
- 📄 Job Seekers can save jobs, apply with resume upload, and track application status
- 🏢 Employers can post, edit, and delete jobs and review applicants
- 👮 Admin can block, unblock, or delete users
- 💾 SQLite database with SQLAlchemy ORM

---

## 🛠️ Tech Stack

| Layer      | Technology                        |
|------------|-----------------------------------|
| Backend    | Python, Flask                     |
| Database   | SQLite, Flask-SQLAlchemy          |
| Auth       | Flask-Login, Werkzeug (bcrypt)    |
| Frontend   | HTML, Bootstrap, Jinja2           |
| APIs       | Remotive API, Arbeitnow API       |

---

## 📂 Project Structure

```
job_portal_project/
├── app.py          # Main Flask app and routes
├── models.py       # Database models
├── requirements.txt
├── uploads/        # Uploaded resumes
└── templates/      # HTML pages
    ├── index.html
    ├── login.html
    ├── register.html
    ├── jobs.html
    ├── post_job.html
    ├── apply_internal.html
    ├── my_applications.html
    └── admin.html
```

---

## ⚙️ How to Run

```bash
# 1. Clone the repository
git clone https://github.com/nirikshan9611/Job-Portal-Flask-Web-App.git
cd Job-Portal-Flask-Web-App

# 2. Install dependencies
pip install flask flask-login flask-sqlalchemy flask-wtf requests werkzeug

# 3. Run the app
python app.py
```

Open your browser and go to: `http://127.0.0.1:5000`

---

## 👤 User Roles

| Role       | What they can do                                      |
|------------|-------------------------------------------------------|
| Job Seeker | Search jobs, save jobs, apply, track application status |
| Employer   | Post jobs, edit/delete jobs, view applicants          |
| Admin      | Block/unblock/delete users, view all data             |

---

## 👨‍💻 Developed By

**Nirikshan K**  
GitHub: [github.com/nirikshan9611](https://github.com/nirikshan9611)
