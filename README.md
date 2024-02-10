# 🏥 Huduma-Health 🚀

## 🌐 Overview
Huduma Health is a web-based application built with Django, designed to streamline services at a healthcare facility. It allows both hospital staff and patients to interact with the system seamlessly and access these services on the go. 🏃‍♀️🏃‍♂️

## 🎁 Features
- 📝 User registration
  - 🧑‍⚕️ Patients
      - 📅 View their requested appointments
      - 🧾 View invoices
      - 💰 View payments
      - 👤 Manage their profile and medical history
  - 👨‍⚕️ Doctors
      - 📅 View allocated appointments
      - 💊 Make prescriptions
      - 👤 Manage their profile
- 👑 Admin (Superuser)
  - Perform CRUD operations on:
    - 👥 User Profiles
      - 🧑‍⚕️ Patients
      - 👨‍⚕️ Doctors
      - 👑 Superusers
    - 📅 Appointments
    - 🧾 Patient Invoices
    - 💰 Payments
    - 💊 Prescriptions

## 🤝 Contributing to the project
To set up, install, and run this project:

1. 📂 Clone the repository
```bash
git clone https://github.com/RBeNturi/Huduma-Health.git
```
2. 🚀 Navigate to the project directory
```
cd Huduma-Health
```
3. 📦 Install the project dependencies
```
pip install -r requirements.txt
```
4. 🌐 Activate the virtual environment
```
source venv/bin/activate
```
5. 🔄 Apply migrations
```
python manage.py migrate
```
6. 👑 Create a superuser
```
python manage.py createsuperuser
```
7. 🚀 Run the development server
```
python manage.py runserver
```
