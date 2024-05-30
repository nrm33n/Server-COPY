# About
This is a slightly altered (and as of May 2023 outdated) copy of the source code for my <a href="http://bastaki.pythonanywhere.com/">Bastaki site</a>. I built it as a resource to aid research and preservation for Bastaki, my community's endangered dialect of the Ajami language. 

Im not publishing the entire original source code b/c it includes some sensitive data. Also removed the database & info pages here because this is an ongoing, continuously updated project, don't want to leave incorrect or outdated information lying around but they're still publically available on <a href="http://bastaki.pythonanywhere.com/">bastaki.pythonanywhere.com</a>.

# Technologies 
![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)
![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)
![Jinja](https://img.shields.io/badge/jinja-white.svg?style=for-the-badge&logo=jinja&logoColor=black)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)

I also used some AJAX to help pass data around a little more cleanly.   

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
# Colour palette 
| Colour  | Hex |
| ------------- | ------------- |
| light-olive  | <img valign='middle' style='square' src='https://readme-swatches.vercel.app/f8f8f8'/> #f8f8f8  |
| med-light olive  | <img valign='middle' style='square' src='https://readme-swatches.vercel.app/dce1d7'/> #dce1d7 |
| med-olive | <img valign='middle' style='square' src='https://readme-swatches.vercel.app/c7d1b6 '/> #c7d1b6 | 
| deep-olive | <img valign='middle' style='square' src='https://readme-swatches.vercel.app/7a8967 '/> #7a8967 | 
