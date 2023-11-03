# Социальная сеть YaTube

[![CI](https://github.com/yandex-praktikum/hw05_final/actions/workflows/python-app.yml/badge.svg?branch=master)](https://github.com/yandex-praktikum/hw05_final/actions/workflows/python-app.yml)

YaTube это платформа для публикации пользовательских статей на фреймворке Django. Пользователи могут создавать свои публикации, описывать а также добавлять картинки, также есть возможность редактировать свои публикации. Пользователи могут просматривать страницы других авторов, подписываться на них и оставлять комментарии.
<br>Проект можно посмотреть по ссылке https://mutsolgov.pythonanywhere.com/


### Установка и настройки
___

#### *Клонируем проект:*
```python
git clone git@github.com:mutsolgov/hw05_final.git
```

#### *Переходим в папку с ботом.*
```
cd hw05_final
```


*Создаем виртуальное окружение:*
```
python -m venv venv
```

*Запускаем виртуальное окружение:<br>*
```
source venv/Scripts/activate 
``` 

*Устанавливаем зависимости:<br>*
```
python -m pip install --upgrade pip
pip install -r requirements.txt
```

*Выполняем миграции:*
```
python manage.py makemigrations
python manage.py migrate
```

Создаем суперпользователя:
```
python manage.py createsuperuser
```

*Запускаем проект.*
```
python manage.py runserver
```

### *Автор:<br>*
### *Муцольгов Магомед 2023 год.*
