Проект представляет собой API для социальной сети Yatube.

### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone git@github.com:YaMaxPy/api_yatube.git
```

```
cd api_yatube
```

Cоздать и активировать виртуальное окружение:

```
python -m venv env
```

```
source venv/Scripts/activate
```

Установить зависимости из файла requirements.txt:

```
python -m pip install --upgrade pip
```

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python manage.py migrate
```

Запустить проект:

```
python manage.py runserver
```

Документация к API доступна по адресу http://127.0.0.1:8000/redoc/ после запуска сервера с проектом.

#### Ключевые технологии и библиотеки:
- [Python](https://www.python.org/);
- [Django](https://pypi.org/project/Django/);
- [Django REST framework](https://pypi.org/project/djangorestframework/);

#### Автор
- [Радченко Максим](https://github.com/YaMaxPy "GitHub аккаунт")
