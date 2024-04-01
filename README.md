# Creating a todo list web app

I am reproducing this amazing tutorial (https://youtu.be/Z1RJmh_OqeA)

# Key functionalities
- add a task with the date of creation included
- update an existing task
- delete a listed task

# first

create a virtual environment and activate it

    python -m venv <virtualenv name>

    <virtualenv name>\Scripts\activate

# tools
flask, html, css, heroku, jinja, sqllite

# scripts and folders in this repo

# app script
- contains the flask routes.
- and the sqlite database connection

template inheritance
- we use a base.html template to contain boiler plate stuff.

jinja statements
- Flask uses them for dynamic updating of variables.

setting up the database
- we set up a model in app.py

some css to style the page.
procfile was supposed to help with deploying with heroku, but i will try deploying with kenet instead ( i will share shortly about that)

check out the app the ![app ui](https://github.com/Antony-gitau/task-manager/blob/main/static/assets/app-ui.png))

