# Проект api_final_yatube
## Описание
API приложение для работы с постами, комментариями в постах и подписками

## Установка
Склонируйте с git
```
https://github.com/yandex-praktikum/api_final_yatube.git
```
Разверните venv
```
python3 -m venv venv
```
Установите зависимости
```
pip install -r requirements.txt
```
Выполните миграции
```
python manage.py migrate
```
Запустите проект
```
python manage.py runserver
```