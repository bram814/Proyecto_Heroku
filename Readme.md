### - windows-
pip install  Flask
pip install virtualenv
python -m venv venv

--------------------------

Ingresar a la carpeta Scripts y usar activate para activar el entorno virtual, luego instale todas las librerías.(activate)
1. pip install flask
2. pip install gunicorn
3. pip install flask-codemirror
4. pip install Flask-WTF

pip freeze > requirements.txt
agregar archivo -> Profile
	web: gunicorn app:app



1) heroku login
2) heroku git:remote -a nombreapp

___________________________________

### -ubuntu -
1. pip install Flask
2. pip install virtualenv

3. virtualenv env -p python3

4. source Fronted/src/env/bin/activate
5. pip install Flask
6. pip install gunicorn
7. pip install flask-codemirror
8. pip install Flask-WTF

9. pip freeze > Fronted/src/requirements.txt

10. curl https://cli-assets.heroku.com/install-ubuntu.sh | sh

11. heroku login -i

12. heroku git:remote -a codemirror-app

13. git push heroku master