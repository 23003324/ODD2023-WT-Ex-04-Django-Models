# Ex-04-Django-Models

Name:Haritha Ramesh

Reference Number: 23003324

Department: CSE(cyber security)

## AIM:
To create a Django model.
## PROCEDURE:
## Step1 : Create django project and app using the following commands:

Django-admin startproject mymodels

Python manage.py startapp myapp

## Step 2: create a user_profile models in model.py


![Alt text](model.png)



Add the models in the admin interface using the code in admin.py

![Alt text](admin.png)




Write the function based view to render the data from the models to the template in view.py

![Alt text](view.py.png)




Setup the url path for the templates using urls.py


![Alt text](urls.png)



In settings.py file add the app created.

## STEP 3: Now do the migrations process to initiate and save the models

Python mange.py makemigrations
Python manage.py migrate
Create a template as user_profiles.html


![Alt text](profile.png)



## STEP 4: Run the program using the command

Python manage.py runserver 8000

In the admin/ page you can view the models created

And  in the user_profile template page you can see the profile page of the user.

## OUTPUT:



![Alt text](<Screenshot 2023-11-10 115340.png>)




![Alt text](models.png)
## RESULT:
Thus the Django model created successfully.
