#### FlaskTut -- flask tutorial Brad Traversy - 08/2019

  * build & deploy
  * mailtrap.io
  * https://picsum.photos/images
  * `pip3 install flask`
  * postgresql: 
    - `sudo apt install postgresql postgresql-contrib`
    - `sudo apt install libpq-dev`
    - `pip3 install psycopg2`
    - `pip3 install psycopg2-binary`
    - `pip3 install flask-sqlalchemy`
    - `pip3 install gunicorn` - for heroku
  * deploy -- general stuff, Brad deploys to Heroku
    - initial installs: python3, pip, postgres
    - create db
    - create folder(s) for content
    - clone from github
    - pip install all requirements (requirements.txt) `pip install -r requirements.txt` 
    - change database URI in app.py
    - change ENV in app.py to production
    - create table:
      * `python`
      * `from app import db`
      * `db.create_all()`
      * `exit()`


