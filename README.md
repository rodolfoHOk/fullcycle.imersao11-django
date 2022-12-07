# Imersão Fullstack & FullCycle 11 - Cartola FullCycle

> Microsserviço Django

## Tecnologias

- Python
- Django

## Guia

- Instalando o Django: pipenv install django
- Entrar no shell do venv: pipenv shell
- Iniciar projeto Django: django-admin startproject cartola_fc
- Rodar migrações do Django (cria banco de dados com sqlite): python manage.py migrate
- Rodar o servidor Django: python manage.py runserver 0.0.0.0:8000
- Criar super usuário do projeto Django: python manage.py createsuperuser / admin@user.com / secret
- Criando um módulo no projeto: django-admin startapp app
- Adicionar módulo ao projeto Django: em cartola_fc/settings.py INSTALLED_APPS adicionar app
- Criar migrations a partir dos models: python manage.py makemigrations
- Rodar migrações dos models: python manage.py migrate
- Registrar models no admin: em app/admin.py adicionar admin.site.register(Player) e importação do Player
- 

## Links dos repositórios da Imersão

- https://github.com/rodolfoHOk/fullcycle.imersao11-consolidacao
- https://github.com/rodolfoHOk/fullcycle.imersao11-django
