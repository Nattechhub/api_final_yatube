# Описание
API для Yatube - это проект социальной сети в которой реализованы следующие возможности:
* подписка на авторов
* публикация записей
* комментирование постов

## Стек технологий

* Python 3.7.9,
* Django,
* DRF,
* JWT
* Djoser 2.10

# Как запустить проект:

## Клонировать репозиторий и перейти в него в командной строке:

```
git clone git@github.com:Nattechhub/api_final_yatube.git
```

```
cd yatube_api
```

## Cоздать и активировать виртуальное окружение:

### Для MacOs и Linux
```
python3 -m venv venv 
```

```
source env/bin/activate
```
### Для Windows
```
python -m venv venv 
```

```
source venv/Scripts/activate
```

## Установить зависимости из файла requirements.txt:

### Для MacOs и Linux
```
python3 -m pip install --upgrade pip
```

```
pip install -r requirements.txt
```

### Для Windows
```
python -m pip install --upgrade pip
```

```
pip install -r requirements.txt
```

## Выполнить миграции:

### Для MacOs и Linux
```
python3 manage.py migrate
```
### Для Windows
```
python manage.py migrate
```

Запустить проект:

### Для MacOs и Linux
```
python3 manage.py runserver
```

### Для Windows
```
python manage.py runserver
```

## Документация к API проекта Yatube находится по ссылке:
`<link>` :    http://127.0.0.1:8000/redoc/
