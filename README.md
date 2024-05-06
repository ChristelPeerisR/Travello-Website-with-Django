# Travello-Website-with-Django

## Live Demo:

https://github.com/ChristelPeerisR/Travello-Website-with-Django/assets/83603996/fe440c44-ac69-4184-9bf0-73a71a04d666

## Functions

### Admin
- Create Admin account and Login.
- Can add new Places, blogs and all required models.

### User
- Create user login.
- Can add products to cart.
- Can filter products upon its's category, min-max price and offers.
- Can view Gallery.
- Can read Blogs.

## HOW TO RUN THIS PROJECT

### Prerequisites
- Python 3.12.0 installed (Ensure to select "Add to Path" during installation)

### Steps
1. Download the project ZIP folder and extract it.
2. Open your terminal or command prompt.

3. Install project dependencies by executing the following command:
```
python -m pip install -r requirements.txt
```
```
cd path/to/project/folder
```
```
py manage.py makemigrations
```
```
py manage.py migrate
```
```
py manage.py runserver
```
Once the server is running, open your web browser and enter the following URL:
```
http://127.0.0.1:8000/
```

These instructions provide clearer steps, organize the commands logically, and include a section on prerequisites for better understanding.

### CHANGES REQUIRED FOR DATABASE MANAGEMENT
In settins.py file, You have to give your username and password<br>
DATABASES = {<br>
    'default': {<br>
        'ENGINE': 'django.db.backends.postgresql',<br>
        'NAME': 'DB Name',<br>
        'USER':'postgres',<br>
        'PASSWORD':'Ypur password',<br>
        'HOST':'localhost'<br>
    }<br>
}<br>

## Contact & Feedback
Email: christelpeeris@gmail.com



