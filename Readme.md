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