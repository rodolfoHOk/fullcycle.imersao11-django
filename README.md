# Imersão Fullstack & FullCycle 11 - Cartola FullCycle

> Microsserviço Django

## Principais Tecnologias

- Python
- Django
- SQLite

### Bibliotecas adicionais

- django-environ
- dj-database-url
- djangorestframework
- django-cors-headers

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
- Signals e Receivers do Django: signals corresponde a events e receivers corresponde a listeners em outros frameworks
- Biblioteca django-environ: serve para pegar as variáveis de ambiente com tipagem
- Biblioteca dj-database-url: serve para segregar automaticamente a variável de ambiente DATABASE_URL no formato que o Django utiliza
- Fazer um dump dos dados do módulo no banco: 
  - dump módulo app: python manage.py dumpdata app (pegar tudo)
  - dump módulo auth: python manage.py dumpdata auth (pegar o último model)
- Carregar dados iniciais: python manage.py loaddata initial_data

## Links dos repositórios da Imersão

- https://github.com/rodolfoHOk/fullcycle.imersao11-consolidacao
- https://github.com/rodolfoHOk/fullcycle.imersao11-django
- https://github.com/rodolfoHOk/fullcycle.imersao11-next
