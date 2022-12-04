# BITES APP


## Getting Started
<hr>

### Initials
<hr>

 - Navigate to the location where the cloned project will be pulled into.
 - Use the command line to run `git clone <code_url>` whereby the `code_url` is found in github repo.
 - Navigate to the `BITESAPP` folder.
 - Initiate the command in the terminal to make a virtual environment.
    ````python -m venv venv````
 - Install the requirements by using the command `pip install -r requirements.txt`.
 - Create the required db and user in psql and remember to change the `DATABASES` dictionary settings including `NAME`, `PASSWORD`, `HOST` AND `PORT` in `settings.py`.
 - Make migrations `python manage.py makemigrations`.
 - Migrate `python manage.py migrate`.
 - In the terminal within the `BITESAPP` folder, create a superuser using the command `python manage.py createsuperuser`. Fill in the `username`, `email` and `password`.
 - Run the live-server `python manage.py runserver`.

 <hr>

 ### Environment variables
 <hr>

 - Create `.env` file and place it into the same directory with settings.py
 - Final step is; Inside the .env file add the following lines:
 > SECRET_KEY=`secret_key` which is obtained by generating at [djecrety](https://djecrety.ir/) <br>
 NAME=`database_name` <br>
 USER=`user_name_db` <br>
 PASSWORD=`your_password` <br>
 
 NOTE: Don't leave any spaces i.e it should be: NAME=my_project_db. <br>
 <b> More information about django-environ can be found [here at ZappyCode](https://zappycode.com/tutorials/keep-secrets-secret-how-to-hide-sensitive-data-in-django) or in the [official docs](https://django-environ.readthedocs.io/en/latest/quickstart.html) </b> <br>
 
