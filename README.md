# MT_Django_API


Project details :
The Aim of the project was to execute the following
1.Make a Django application
2.Migrate it to FastAPI
3.Use config based development  , follow good coding practices , write comments and documentations and put logs
3.Package it (Using poetry module packaging)
4.Host on Windows services and/or IIS

How to execute this File:

Method 1:
1. Navigate to Django_API_Main\dist\crud_api-0.1.0.tar.gz and download the tar.gz file
2. Open terminal with path of the folder in which tar.gz file is saved
3. Execute the following in the terminal 
           tar -xzf crud_api-0.1.0.tar.gz
           cd crud_api-0.1.0
4. Run the following python command(Install Python if already not installed) to create and activate virtual environment.
           python -m venv venv
           venv\Scripts\activate
5. Run the following 
           pip install poetry
           poetry install
           cd crud_api
           python manage.py migrate
           python manage.py runserver
This will launch the Django server, you can view the source code in the crud_api folder

Method 2:
1. Navigate to Django_API_Main\dist\crud_api-0.1.0-py3-none-any.whl and download the .whl file
2. Open terminal with path of the folder in which tar.gz file is saved
3. Execute the following in the terminal 
Run the following python command(Install Python if already not installed) to create and activate virtual environment.
           python -m venv venv
           venv\Scripts\activate
4. Run the following 
           pip install crud_api-0.1.0-py3-none-any.whl
           cd "venv\Lib\site-packages\crud_api"
           python manage.py migrate
           python manage.py runserver
This will launch the Django server, you can view the source code in the crud_api folder

Application details:
This is a basic CRUD in Django, written for the purpose of executing project Aim 


