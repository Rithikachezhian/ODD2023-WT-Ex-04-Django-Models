# Ex-04-Django-Models
NAME:RITHIKA
REFERENCE NUMBER:23013374
Department:AIDS
AIM:
To create django model

DESIGN PROCEDURE
Django models

step 1: Create django project and app using the following commands django-admin startproject mymodels python manage.py startapp myApp

step 2: create a user_profile models in model.py
![Screenshot 2024-01-04 104416](https://github.com/Rithikachezhian/ODD2023-WT-Ex-04-Django-Models/assets/145742406/15030e8e-39a4-416b-9497-a9689571090b)
add the models in the admin interface using the code admin.py
![Screenshot 2024-01-04 104509](https://github.com/Rithikachezhian/ODD2023-WT-Ex-04-Django-Models/assets/145742406/415c694c-703b-4f0c-be54-b837266b3c0c)
write the function based view to render the data from the models to the template in views.py
![Screenshot 2024-01-04 104613](https://github.com/Rithikachezhian/ODD2023-WT-Ex-04-Django-Models/assets/145742406/fb5ee431-d003-43b1-a517-df0273b26b7b)
set up the url path for the templates using urls.py
![Screenshot 2024-01-04 104721](https://github.com/Rithikachezhian/ODD2023-WT-Ex-04-Django-Models/assets/145742406/8d39cc47-281a-4d59-b80b-550586eff804)
in settings.py file add the appcreated

step 3: Now do the migrations process to initiate and save the models

python manage.py makemigrations python manage.py migrate create a template as user_profile.html

step4: Run the program using the following command

python manage.py runserver 8000 in the admin page you can view the models created and in the user_profile template page you can see the profile page of the user
Output:
Result:
Django model was created successfully


