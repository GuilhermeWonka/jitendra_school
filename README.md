# Schoolmanagement
![developer](https://img.shields.io/badge/Developed%20By%20%3A-Jitendra%20Saini-red)
---
## screenshots
### Homepage
![homepage snap](https://github.com/sumitkumar1503/schoolmanagement/blob/master/static/screenshots/homepage.png?raw=true)

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

## IDE
- PyCharm Community Edition or visual studio code

## Drawbacks
- On update page of teacher/student you must have to update password.
- Anyone can become Admin

## HOW TO RUN THIS PROJECT
- Install Python(3.12) (Dont Forget to Tick Add to Path while installing Python)
- Open Terminal and Execute Following Commands :
``` 
 python -m venv venv
 venv\Scripts\activate 
 python -m pip install -r requirements.txt 
 pip install setuptools
 pip install django-widget-tweaks
 ```

```
py manage.py makemigrations
py manage.py migrate
py manage.py runserver
```
- Now enter following URL in Your Browser Installed On Your Pc
```
http://127.0.0.1:8000/
```

## CHANGES REQUIRED FOR CONTACT US PAGE
- In settins.py file, You have to give your email and password
```
EMAIL_HOST_USER = 'youremail@gmail.com'
EMAIL_HOST_PASSWORD = 'your email password'
EMAIL_RECEIVING_USER = 'youremail@gmail.com'
```
- Login to gmail through host email id in your browser and open following link and turn it ON
```
https://myaccount.google.com/lesssecureapps
```

## Disclaimer
This project is developed for demo purpose and it's not supposed to be used in real application.


