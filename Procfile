web: gunicorn np.wsgi --log-file -
worker: celery worker -A np -E -l debug
