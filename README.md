# About
This is a slightly altered copy of the source code for my site. I cannot publically publish the original source code as it includes mail passwords. I also removed the database and 
info page here as they are constantly being edited and I don't want to leave incorrect or outdated information lying around but both of those are available on the site. 

This is built with a SQLite database, Flask-based backend, Jinja2 frontend, and styled with Tailwind. I also used some AJAX to help pass data around a little more cleanly.   

# Run steps 
```
set FLASK_APP=app
```
```
set FLASK_ENV=development 
```
Note: if not using Windows, change 'set' to 'export'
```
python3 -m flask run 
```

With a python virtual environment: 
```
virtual\Scripts\python app.py
```

# Watch new tailwind changes 
```
npx tailwindcss -i ./static/src/input.css -o ./static/dist/css/output.css --watch
```
