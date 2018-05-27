# WTF Flask User


# SMTP

To get Google to work with SMTP you will need to create an application password 
in your Google account settings. 

## Runtime

```
    # Clone the code repository into ~/dev/my_app
    mkdir -p ~/dev
    cd ~/dev
    git clone https://github.com/lingthio/Flask-User-starter-app.git my_app

    # Create the 'my_app' virtual environment
    mkvirtualenv -p PATH/TO/PYTHON my_app

    # Install required Python packages
    cd ~/dev/my_app
    workon my_app
    pip install -r requirements.txt

    python manage.py init_db
    python manage.py runserver
```

## Reference

* [FlaskDash](https://github.com/twintechlabs/flaskdash) is a starter app for Flask
  with [Flask-User](https://readthedocs.org/projects/flask-user/)
  and [CoreUI](https://coreui.io/) (A Bootstrap Admin Template).

* [Alembic](http://alembic.zzzcomputing.com/)
* [Flask](http://flask.pocoo.org/)
* [Flask-Login](https://flask-login.readthedocs.io/)
* [Flask-Migrate](https://flask-migrate.readthedocs.io/)
* [Flask-Script](https://flask-script.readthedocs.io/)
* [Flask-User](http://flask-user.readthedocs.io/en/v0.6/)

<!-- Please consider leaving this line. Thank you -->
[Flask-User-starter-app](https://github.com/lingthio/Flask-User-starter-app) was used as a starting point for this code repository.
