## Как запустить проект:
Клонировать репозиторий и перейти в него в командной строке:
```
git clone git@github.com:osipovyakov/api_final_yatube.git
```
```
cd api_final_yatube
```
Cоздать и активировать виртуальное окружение:
```
python -3.7 -m venv venv 
```
```
. venv/Scripts/activate
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
python3 manage.py migrate
```
Запустить проект:
```
python3 manage.py runserver
```

## Примеры запросов к API Вы можете найти по ссылке http://127.0.0.1:8000/redoc/ после запуска проекта
