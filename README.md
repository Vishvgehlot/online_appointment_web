# 🩺 Online Appointment System

A simple Flask-based Online Appointment System where doctors and patients can manage appointments.  
It includes features like doctor signup/login, online status management, patient appointment booking, and a doctor dashboard.

---

## 🚀 Features

- Doctor Signup/Login (stored in `doctors.json`)
- Doctor Dashboard to manage appointments
- Patient Appointment Booking
- Doctor Online/Offline Status
- Pending, Accepted, Rejected Appointments
- Token Number Assignment
- Clean UI with CSS Styling

---

## 📂 Project Structure
```bash
online appointment 3/
│── app.py                # Main Flask application
│
├── data/
│   └── doctors.json       # Stores doctor data
│
├── static/
│   └── style.css          # Stylesheet
│
└── templates/             # HTML templates
    ├── doctor_dashboard.html
    ├── doctor_login.html
    ├── doctor_signup.html
    ├── home.html
    └── patient_view.html
```
---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone <repo_url>
cd "online appointment 3"
```

2. Create a virtual environment (recommended)
```bash
python -m venv venv
```
# On Mac/Linux
```bash
source venv/bin/activate
```
# On Windows
```bash
venv\Scripts\activate
```


3. Install dependencies
```bash
pip install flask
```
▶️ Usage
Run the Flask app:
```bash
python app.py
```
Then open your browser and go to:
http://127.0.0.1:5000/

👨‍💻 Users
Doctors
- Can sign up & log in
- Toggle online/offline status
- Accept/Reject appointment requests
- View patient details (including phone number)
Patients
- Can book appointments
- Can view all their booked appointments
- Get a token number for accepted appointments

📌 Notes
- Doctor data is stored in data/doctors.json.
- This is a lightweight project (no database like SQLite/MySQL).
- Easily extendable with database integration & authentication.
