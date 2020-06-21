# flaskr-blog

## Build and install
- pip install wheel
- python setup.py bdist_wheel

<hr>

## install in another device
- setup devenv
- pip install flaskr-1.0.0-py3-none-any.whl

- set FLASK_APP=flaskr
- flask init-db

## setup config
- venv/var/flaskr-instance/config.py
- SECRET_KEY = /*your secret/*

## Run with a Production Server
- pip install waitress
- waitress-serve --call 'flaskr:create_app'
