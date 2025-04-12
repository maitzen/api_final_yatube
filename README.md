# API_FINAL_YATUBE

Законченная версия API для Yatube c авторизацией по JWT-токену

**СТЕК** Python 3.9, Django Rest Framework, SQLite

## ЗАПУСК ПРОЕКТА

- **Клонировать репозиторий и перейти в него в командной строке:**
  ```sh
  git@github.com:maitzen/api_final_yatube.git

- **Создать и активировать виртуальное окружение:**
  ```sh
  python -m venv venv
  source venv/Scripts/activate

- **Установить зависимости из requirements.txt:**
  ```sh
  python -m pip install --upgrade pip
  pip install -r requirements.txt

- **Выполнить миграции:**
  ```sh
  python manage.py migrate

- **Запустить проект:**
  ```sh
  python manage.py runserver
