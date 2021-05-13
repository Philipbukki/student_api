# student_api
The student api allows a user to perform CRUD operations, that is to
 create, retrieve, update and delete a student object.
 
### How it works

Users can create a student object.

Users can retrieve a list of existing student objects.

Users can update or delete existing student objects.

##### clone this repository

```
git clone https://github.com/Philipbukki/student_api.git

```
change directories into your repository
```console
cd studApi
```
##### create a virtual environment
```console
python3 -m venv env
```
##### activate virtual env

```console
pipenv shell
```

##### install the packages needed.

```console
pipenv install -r requirements.txt
```
##### Make migrations
 
```console
python3 manage.py makemigrations
python3 manage.py migrate
``` 
##### Run the application
```
python manage.py runserver
```

Navigate to http://localhost:8000 in your web browser to view the application.