Клонировать репозиторий и перейти в него в командной строке:

```python
git clone https://github.com/dshubenok/kittygram-auth
cd kittygram-auth
```

Cоздать и активировать виртуальное окружение:

```python
python3 -m venv venv
source venv/bin/activate
```

Установить зависимости из файла requirements.txt:

```python
pip install -r requirements.txt
```

Выполнить миграции:

```python
python manage.py migrate
```

Запустить проект:

```python
python manage.py runserver
```
