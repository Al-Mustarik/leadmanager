# leadmanager
## Backend Command
* mkdir lead_manager_react_django
* cd lead_manager_react_django
* pip install pipenv
* pipenv shell
* pipenv install django djangorestframework django-rest-knox
* django-admin startproject leadmanager
* cd leadmanager
* python manage.py startapp leads
* python manage.py makemigrations leads
* python manage.py migrate
* python manage.py runserver

## Frontend Command (REACT)
--npm init -y
--npm i webpack webpack-cli --save-dev
--npm i @babel/core babel-loader @babel/preset-env @babel/preset-react --save-dev
--npm i react react-dom --save-dev
--npm install @babel/plugin-proposal-class-properties
--npm install react-router-dom
--npm run dev/build
--npm i redux react-redux redux-thunk redux-devtools-extension
--npm i axios
--npm install --save react-alert react-alert-template-basic react-transition-group
