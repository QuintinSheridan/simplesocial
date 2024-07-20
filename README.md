This is a simple social blogging application made using Django version 4.2 and python 3.9.

Build Steps:

1. Create a virtual Environment
virtualenv .env

2. Activate the virtual environment to install requirements
source .env/bin/activate

3. Install dependencies from requirements.txt
pip install -r requirements.txt

4. Create database migrations
python3 manage.py makemigrations

5. Run database migrations
python3 manage.py migrate

7. Run the Server
python3 manage.py runserver

