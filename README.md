For detailed information about this project go to this link: https://www.django-rest-framework.org/tutorial/quickstart/
<br>
or this
https://rapidapi.com/blog/python-django-rest-api-tutorial/

--------------------------------------------------------------------------------------------------------------------------------

**Run these after cloning the process**
-------------------------------------------------------------------------------------------------------------------------------------------
After cloning run these command:

pip3 install -r requirements.txt
python manage.py makemigrations
python manage.py migrate
python manage.py createsuperuser # Create a superuser
python manage.py runserver
After these, Open a browser to http://127.0.0.1:8000/ , one can create user by clicking on the users' url which is http://127.0.0.1:8000/users/ and create grourps by clicking the groups url http://127.0.0.1:8000/groups. These are created using post method, one can see the data after creating. 
