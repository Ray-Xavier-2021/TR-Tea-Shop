# Tea Shop in React & Redux + Django
```
Forum App, with a frontend built in React & Redux and a backend built in Django API.
```
## Live Demo
![tea-shop](https://user-images.githubusercontent.com/78431899/186002093-2a677bba-b07b-4e54-a859-b7b5e6ca68db.png)

**This App uses a Heroku free plan, so I am afraid that it takes time to load the pages.**
Check out [FRONTEND LIVE DEMO](https://sd-tea-shop-frontend.herokuapp.com/) here!!
Check out [API LIVE DEMO](https://backend-horatio.herokuapp.com/) here!!
## Tech used
```
* Frontend : React & Redux
* Backend : Django
```
## How to Install
1. Git Clone
```
git clone https://github.com/Ray-Xavier-2021/TR-Tea-Shop
```
2. Backend setting
```
cd backend
Python -m venv env
(For Mac) source env/bin/activate
(For Windows) env/Scripts\activate
pip install -r requirements.txt
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
# Open http://127.0.0.1:8000/posts/
# To have dummy data for testing run:
python manage.py fixtures/dummy-data.json
```
3. Frontend setting
```
cd frontend
npm install
npm start
# Open http://127.0.0.1:3000/
```
