# Blog Website Using Django

#### Main Features:
* User/Author can Login or Signup initially.
* After Logging In USer can then Create a Blog with Title and Content of the Blog and Publish it on the main page.
* A user can view all the posts of the published on the website.
* User can update and delete their posts.
* A profile section to update the profile of the users.
* A filter section to filter the posts by clicking on the username.
* Pagination to switch between different pages.


## To run this project follow the instructions given below:

#### First Clone the project
```
git clone https://github.com/altamash23820/blog-django.git
cd blog_day
```

#### After cloning, run following commands:-
```
pip install django[argon2]
```
#### After running commands use following commands:
```
python manage.py migrate
python manage.py makemigrations
python manage.py migrate
```

#### Once done with that create a superuser account:
```
python manage.py createsuperuser
```

#### Once superuser account is created we can run the website
```
python manage.py runserver
```

#### If there are no errors website will be running on [http://127.0.0.1:8000/](http://127.0.0.1:8000/) (default)