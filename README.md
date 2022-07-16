# buy-on-the-fly-backend
Buy on the fly backend (E-commerce)

# For the install virtual environment
python3 -m venv env

# To active the virtual environment
source env/bin/activate

# For the first time needs to create .env file and ask content from the admin developer
touch .env

# When there are database context changes needs to run first migraion
python manage.py makemigrations

# To run migration script in the database 
python manage.py migrate

# To run the backend server
python manage.py runserver

# For Windows
.\env\Scripts\activate

