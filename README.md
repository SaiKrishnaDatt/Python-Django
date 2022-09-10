Installing django
CMD : python3 -m pip install Django

------------------------------------
Verifying if django is installed correctly or not 
CMD : django-admin
------------------------------------


first go to your working directory 
cd /Users/ssuddhapally/Documents/Python

------------------------------------
Now create a django project with name mypage
CMD : django-admin startproject mypage
------------------------------------


------------------------------------
run the manage.py file
CMD : python3 manage.py runserver
------------------------------------

when we run the above commond we can preview our application and db.sqlite3 file will be created that is a dummy database


Any folder which is having __init__.py is the module in the code
but in the django world we call it as app
------------------------------------
creating a app in django
CMD : python3 manage.py startapp challenges
------------------------------------