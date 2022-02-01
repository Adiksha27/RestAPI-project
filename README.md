# RestAPI-project
This repo has the code for a Notes API, my first Django RESTful API project. Hope you liked it.

## To Run on Localhost:

- Have `Python` and `pip` installed on your local machine

## Running the Django project:

Create an isolated environment for the project with `virtualenv`. You can install `virtualenv` with the following command:

```
sudo pip install virtualenv
```

Clone the project from GitHub:

```bash
git clone https://github.com/Adiswat/RestAPI-project
```

Navigate to the cloned project directory:

```
cd RestAPI-project
```

Create a virtual environment for the project:

```bash
virtualenv venv
```

Then, activate it:

```bash
.\venv\Scripts\activate (for Windows user)
```

Install Django and Django REST Framework:

```bash
pip install -r requirements.txt
```

Finally, `cd` into the *notes_app* folder and run the project:

```bash
python manage.py runserver
```

Go to http://localhost:8000/ to see if the API is up and running.
**We completed our first REST API project.**
**Happy Coding:)**
