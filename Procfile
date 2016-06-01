web: gunicorn config.wsgi:application
worker: celery worker --app=portale_vm.taskapp --loglevel=info
