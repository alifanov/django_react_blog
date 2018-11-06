# Django react blog

Example of integration React/Redux and Python/Django frameworks in creating blog application

I used pipenv for working with python virtual env. For installing python packages:

```
pipenv --three
pipenv shell
pipenv install
```

## Structure of project

### project

Django project provided API creatd with django-rest-framework.
For run project use:
```
manage.py runserver
```
I you change frontend files you should update them:
```
cd project/frontend
yarn build
```

### project/frontend

React app created with create-react-app. Frontend files connected via django static provider.
You can work only with React app via yarn:
```
cd project/frontend
yarn install
yarn start
```

### project/mobile

React native app created with expo framework.
Run:
```
cd project/mobile
yarn install
export start
```

### project/vision

Test model for example application for face age prediction.
Used by django application.
Or you can use it as CLI:
```
python model.py face.jpg
```
