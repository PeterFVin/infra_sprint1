### О проекте:

Проект Kittygram - социальная сеть для обмена фотографиями любимых питомцев

### Использованные технологии:

Бэкенд разработан на Django REST.
Веб-сервер и обратный прокси-сервер - Nginx.
WSGI-сервер - Gunicorn.
SSL-сертификат на Let's Encrypt.
Мониторинг состояния - UptimeRobot.
База данных - SQLite.

Фронтенд разработан на React.

### Автор проекта:
Петр Виноградов, python plus, когорта 22+

### Как запустить проект:
1. Бэкенд
- Установить зависимости из файла requirements.txt:
pip install -r requirements.txt

- Выполнить миграции:
python manage.py makemigrations

- Запустить проект:
python manage.py runserver

2. Фронтенд
- Установить зависимости
npm i

- Запустить проект
npm run start

### В проекте нужен .env файл
В нём константа SECRET_KEY из settings.py
