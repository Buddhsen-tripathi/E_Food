E_Food

Django based Food Delivery System
Dependencies:
•	Virtualenvwrapper (recommended)  
•	Django Framework
•	Django-crispy-forms
•	Pillow
•	Pymysql (to use MySQL as database) [using sqlite3 as default]

All the above are python libraries you need to install using 'pip intall' command
or by using command pip install -r requirements.txt

Project_name = e_food, App name = main

To install and setup Virtualenv for python version above 3.3

py -m pip install --user virtualenv

For creating new environment:
py -m venv <env-name>

To activate your virtual environment:
.\<env-name>\Scripts\activate

Before running the server, migrate the modules using 
python manage.py makemigrations main //main is the app-name

python manage.py //runs the server on localhost:8000

Login into super-user using given credentials to manage the project @localhost:8000/admin
