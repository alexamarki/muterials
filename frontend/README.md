Frontend service - a Flask-based web app. ALL views are located in views.py, calls to other services are initiated via functions stored in respective files in this service

also, the login state will be cached in order to avoid excessive calls to the authentication service