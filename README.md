### Launching the Project:

Clone the repository and go to it on the command line:

```
https://github.com/boreesych/kittygram_backend.git
```

```
cd kittygram_backend
```

Create and activate a virtual environment:

```
python3 -m venv env
```

```
source env/bin/activate
```

```
python3 -m pip install --upgrade pip
```

Install dependencies from the requirements.txt file:

```
pip install -r requirements.txt
```

Run migrations:

```
python3 manage.py migrate
```

Run the project:

```
python3 manage.py runserver
```
