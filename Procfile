release: python manage.py makemigrations api --no-input
release: python manage.py migrate --no-input
web: gunicorn RecruitAI_backend_ResumeAnalyser.wsgi
worker: celery -A RecruitAI_backend_ResumeAnalyser worker -l info