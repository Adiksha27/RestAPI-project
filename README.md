# RestAPI-project
This repo has the code for a Notes API, my first Django RESTful API project. Hope you liked it.

## To Run on Localhost:

- Have `Python` and `pip` installed on your local machine

## Running the Django project:

Create an isolated environment for the project with `virtualenv`. You can install `virtualenv` with the following command:

```
pip install virtualenv
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

Go to http://localhost:8000/api/ to see if the API is up and running to create notes:):
<img width="946" alt="Screenshot (173)" src="https://user-images.githubusercontent.com/60068360/151931914-8fc119db-b2e3-4ea9-9939-019a6d3487c1.png"> 
You can add notes and refresh the webpage to see the added notes and then, view the created notes at 127.0.0.1:8000/api/id (e.g. 127.0.0.1:8000/api/3):
<img width="945" alt="Screenshot (175)" src="https://user-images.githubusercontent.com/60068360/151931966-5b4ca741-cac2-4d54-a221-56a601938341.png">
You can also delete or update the note on the detail page. Thank you:).

**Eureka! We have completed our first REST API project.**
**Happy Coding:)**
