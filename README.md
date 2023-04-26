# List--Reactjs-DjangoRestframe


![Screenshot (9)](https://user-images.githubusercontent.com/118424866/234658397-bd34ba84-6744-43af-97e1-3c6d0fb71f90.png)



1. Git Clone

```
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
