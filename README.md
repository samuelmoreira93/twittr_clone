#### To use/configure it:

1. Create a virtual environment 

````python -m venv socialenv```.


2. Install the dependencies/libraries in requirements.txt

````pip install -r requirements.txt```


3. Run the migrations.

````python manage.py makemigrations````
````python manage.py migrate```


4. Create a superuser.

````python manage.py createsuperuser````

5. Run the server.

````python manage.py runserver```