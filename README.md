# Huduma-Health
## Overview
Huduma Health is a web based application in Django designed to streamline some services at a healthcare facility. Both hospital staff and patients can seamlessly interact with the system and access these services on the go.
## Features
- User registration
  - Patients
      - View their requested appointments
      - View invoices
      - View payments
      - Manage their profile and medical history
  - Doctors
      - View allocated appointments
      - Make prescriptions
      - Manage their profile
- Admin(Superuser)
  - Perform CRUD operations on:
    - User Profiles
      - Patients
      - Doctors
      - Superusers
    - Appointments
    - Patient Invoices
    - Payments
    - Prescriptions
## Contributing to the project
To set up, install and run this project:
1. Clone the repository
```bash
git clone https://github.com/RBeNturi/Huduma-Health.git
```
2. Navigate to the project directory
```bash
cd Huduma-Health
```
3. Install the project dependencies
```bash
pip install -r requirements.txt
```
3. Activate the virtual environment
```bash
source venv/bin/activate
```
4. Apply migrations
```bash
python manage.py migrate
```
5. Create a superuser
```bash
python manage.py createsuperuser
```
6. Run the development server
```bash
python manage.py runserver
```
