# student_api
**How run studApi**

```console
cd studApi
```

activate virtual env

```console
pipenv shell
```

install requirements.

```console
pipenv install -r requirements.txt
```
 making and running migrations

```console
python3 manage.py runserver
```
```console
python3 manage.py makemigrations
```
```console
python3 manage.py migrate
```
run server

open port http://127.0.0.1:8080
