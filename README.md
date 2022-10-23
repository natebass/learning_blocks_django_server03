# Learning Blocks Django web server
## How to run the project
#### Run web server
```shell
python manage.py runserver
```
#### Run all tests
```shell
python manage.py test
```
### Initial set up
Before running the project, install the python required dependencies. See "Optional requirements to install a virtual environment before installing dependencies."
#### Install requirements
```shell
pip install -r requirements.txt
```
#### Run Django mirgration
```shell
python manage.py migrate
```
Optionally, run this to be prompted to create an administrator user.
#### Create admin user
```shell
python manage.py createsuperuser
```
### Requirements
Python 3

### Optional requirements
Set up venv or conda before installing requirements with pip.