# qotd
Quote_of_the_day

daily-quotes/
├── .github/
│   └── workflows/
│       └── deploy.yml      # CI/CD Pipeline
├── config/
│   ├── settings/
│   │   ├── base.py
│   │   ├── production.py
│   │   └── development.py
│   ├── urls.py
│   ├── wsgi.py
│   └── .env.example
├── quotes/
│   ├── migrations/
│   ├── templates/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   └── views.py
├── requirements/
│   ├── base.txt
│   ├── development.txt
│   └── production.txt
├── .gitignore
├── Dockerfile
├── manage.py
├── runtime.txt
└── build.sh
