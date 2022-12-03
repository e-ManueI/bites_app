# BITES APP


## Getting Started
<hr>

 - Navigate to the location where the cloned project will be pulled into.
 - Use the commandline to run `git clone <code_url>` whereby the `code_url` is found in github repo.
 - Navigate to the `BITESAPP` folder.
 - Initiate the command in the terminal to make a virtual environment.
    ````python -m venv venv````
 - Install the requirements by using the command `pip install -r requirements.txt`.
 - Create the required db and user in psql and remember to change the `DATABASES` dictionary settings including `NAME`, `PASSWORD`, `HOST` AND `PORT` in `settings.py`.
 - Make migrations `python manage.py makemigrations`.
 - Migrate `python manage.py migrate`.
 - In the terminal within the `BITESAPP` folder, create a superuser using the command `python manage.py createsuperuser`. Fill in the `username`, `email` and `password`.
 - Run the live-server `python manage.py runserver`.
 
