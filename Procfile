heroku buildpacks: clear
heroku buildpacks: add--index heroku / python
heroku ps:scale web=1
web: python appMain.py runserver 0.0.0.0:5000