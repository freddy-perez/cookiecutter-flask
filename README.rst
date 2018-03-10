cookiecutter-flask
==================

A Docker Compose Flask template for `cookiecutter <https://github.com/audreyr/cookiecutter>`_. 
The Templates Generates a docker-compose application with 3 containers: Nginx, postgres and flask application.

Use it now
----------
::

    $ pip install cookiecutter
    $ cookiecutter https://github.com/freddystban/cookiecutter-flask.git
You will be asked about your basic info (name, project name, app name, etc.). This info will be used in your new project.

Features
--------

- Bootstrap 3 and Font Awesome 4 with starter templates
- Flask-SQLAlchemy with basic User model
- Easy database migrations with Flask-Migrate
- Flask-WTForms with login and registration forms
- Flask-Login for authentication
- Flask-Bcrypt for password hashing
- Procfile for deploying to a PaaS (e.g. Heroku)
- pytest and Factory-Boy for testing (example tests included)
- Flask's Click CLI configured with simple commands
- CSS and JS minification using webpack
- npm support for frontend package management
- Caching using Flask-Cache
- Useful debug toolbar
- Utilizes best practices: `Blueprints <http://flask.pocoo.org/docs/blueprints/>`_ and `Application Factory <http://flask.pocoo.org/docs/patterns/appfactories/>`_ patterns

Screenshots
-----------

.. image:: https://user-images.githubusercontent.com/2379650/35603073-7f5b78c2-0609-11e8-8fa8-7c6cce27fed6.png
    :alt: Home page

.. image:: https://user-images.githubusercontent.com/2379650/35603086-936a30e2-0609-11e8-8f63-a4c844310aab.png
    :alt: Registration form



Inspiration
-----------

- `Sloria <https://github.com/sloria/cookiecutter-flask>`_


License
-------

BSD licensed.
