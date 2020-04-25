# Django, Vuejs, webpack

Example of running Vue and Django.  This runs with Django serving everything instead of Nodejs, but 
still lets us use the Vue single file components.

Based on this [tutorial](https://github.com/michaelbukachi/django-vuejs-tutorial)

Run webpack:
```
node_modules\.bin\webpack
```

Run django server:
```
python manage.py runserver
```

Hot reloading is not enable - after changes in the Vue templates webpack has to be run again.