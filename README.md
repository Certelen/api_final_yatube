# Cервис YaTube.

## Описание
Сервис блога с возможностью регистрации пользователей, создания публикаций, групп, с возможностью взаимодействия через API.

## Технологии
- Python 3.7
- Django 3.2

# Установка
## Документация
# Копирование репозитория
Клонируем репозиторий
```
~ git clone git@github.com:Certelen/yatube_project_API.git
```
Переходим в клонированный репозиторий
```
~ cd {путь до папки с клонированным репозиторем}
~ cd yatube_project_API
```
Устанавливаем и активируем виртуальное окружение
```
~ py -3.7 -m venv venv
~ . venv/Scripts/activate
```
Устанавливаем требуемые зависимости:
```
~ pip install -r requirements.txt
```
# Миграция базы данных
Применяем миграцию для базы данных:
```
~ python manage.py migrate
```
# Запуск
Запуск сервиса производится командой:
```
~ python manage.py runserver
```
Доступ к сервису становится доступен по [адресу](http://127.0.0.1:8000/)

# Примеры запросов
GET [list of commands with examples](http://127.0.0.1:8000/redoc/#tag/api),

GET [list of posts](http://127.0.0.1:8000/api/v1/posts/),
### Авторы
- :white_check_mark: [Коломейцев Дмитрий(Certelen)](https://github.com/Certelen)
