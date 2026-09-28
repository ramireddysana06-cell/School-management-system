# Schoolmanagement
![developer](https://img.shields.io/badge/Developed%20By%20%3A-Ramu%20Kumar-red)
---
## screenshots
### Homepage
![homepage snap](https://github.com/Ramukumar1503/schoolmanagement/blob/master/static/screenshots/homepage.png?raw=true)
### Admin Dashboard
![dashboard snap](https://github.com/Ramukumar1503/schoolmanagement/blob/master/static/screenshots/adminhomepage.png?raw=true)
### Admin Manage Teacher
![invoice snap](https://github.com/Ramukumar1503/schoolmanagement/blob/master/static/screenshots/adminteacher.png?raw=true)
### Attendance
![doctor snap](https://github.com/Ramukumar1503/schoolmanagement/blob/master/static/screenshots/attendance.png?raw=true)
### Teacher Dashboard
![doctor snap](https://github.com/Ramukumar1503/schoolmanagement/blob/master/static/screenshots/teacher.png?raw=true)
---

## Functions
### Teacher
First the teacher will apply for job,if he/she gets selected there accounts will be made and approved by the admin, after approval only teacher can access their dashboard.
After account approval by admin, teacher can take attendance of any class and view their attendance later.
Teacher can also publish/announce notice to student like submission of assignments.

## Student
First student will take admission/signup.
When their account is approved by admin, only then the student can access their dashboard.
After account approval by admin the student can view their details like attendance.
Student can't view attendance of other student.
Student can't announce, they can only view.

### Admin
First admin will signup for a account.
After login they can see how many student/teacher wants to get job/admission in their school.
They can approve or delete/cancel the request.
They can update any student/teacher details.
Admin can announce notice also.


## Drawbacks
- On update page of teacher/student you must have to update password.
- Anyone can become Admin

## HOW TO RUN THIS PROJECT
- Install Python 3.12 or newer (make sure Python is available in your terminal)
- Open Terminal and Execute Following Commands :

- Download This Project Zip Folder and Extract it
- Move to project folder in Terminal. Then run following Commands :
```
py -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```
- Now enter following URL in Your Browser Installed On Your Pc
```
http://127.0.0.1:8000/
```

## CHANGES REQUIRED FOR CONTACT US PAGE
- Configure a Gmail account with 2-Step Verification, then create an App Password at https://myaccount.google.com/apppasswords.
- The sender and recipient default to the project owner's Gmail address. In PowerShell, set that account's App Password before starting Django. Optionally set `EMAIL_RECEIVING_USER` to deliver messages to a different inbox:
```
$env:EMAIL_HOST_PASSWORD = "your-16-character-app-password"
$env:EMAIL_RECEIVING_USER = "recipient@example.com"
python manage.py runserver
```
- Do not use your normal Gmail password or store the App Password in source code.

For deployment, set a unique `DJANGO_SECRET_KEY`, set `DEBUG=False`, and configure `DJANGO_ALLOWED_HOSTS` for your domain.

## Disclaimer
This project is developed for demo purpose and it's not supposed to be used in real application.

## Feedback
Any suggestion and feedback is welcome. You can message me on facebook
- [Contact on Facebook](https://fb.com/Ramu.luv)
- [Subscribe my Channel LazyCoder On Youtube](https://youtube.com/lazycoders)
