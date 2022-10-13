# django-react-rental

Blog web application written using Javascript with React for Frontend, Python with Django for Backend and PostgreSQL as a default database.

## Features

- Publish posts as a verified staff member
- Read public posts
- Fully functional user with password veryfing/reseting using e-mail
- Authentication thanks to JWT Tokens

## Screenshots


1. First clone the repository to use it localy:

2. Now you need to create a Postgre database with name `blog_db` then do all the migrations using command:

3. Execute SQL File with name `public.sql` in blog_db of  the Postgre database

4. For the frontend you need to run these commands from the `/frontend` folder:

        npm install

    to download all the needed NPM packages and then to start the frontend Dev server:

        npm run dev

5. Finally you can start the frontend server from base project folder by running:
        py -m venv env
        .\env\Scripts\activate
        py manage.py runserver
