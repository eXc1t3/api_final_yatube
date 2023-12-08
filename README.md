### API для Yatube
Учебный проект от Яндекс.Парктикума по курсу Python-разработчик.

### Описание
Yatube - это социальная сеть, в которой реализованы возможности публикации, комментирования записей, а так же подписки и отписки от авторов.

### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/eXc1t3/api_final_yatube
```

```
cd api_final_yatube
```

Cоздать и активировать виртуальное окружение:

```
python -m venv venv
```

```
source venv/Scripts/activate
```

Установить зависимости из файла requirements.txt:

```
pip install -r requirements.txt
```

```
python -m pip install --upgrade pip
```

Выполнить миграции:

```
python manage.py migrate
```

Запустить проект:

```
python manage.py runserver
```

При необходимости установить Djoser

```
pip install -U djoser
```

### Технические требования
Для запуска проекта необходимо установить Python 3.11+ (https://www.python.org/)
