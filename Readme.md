# Flask uWSGI nginx Alpine Docker

This is a docker designed to deploy Flask application using uWSGI in nginx on Alpine.

## Version

* Alpine: 3.7
* Python: 3.6.5
* nginx: mainline

## Usage

Put you project in `/app`. It need to start with `app.py` with `app = Flask`.

## Customization

You can change `app.conf`, `supervisord.ini` and `uwsgi.ini`.