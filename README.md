# API для Yatube

Само название проекта говорит о том, что мы получаем доступ к ранее написанному проекту, социальной сети [Yatube](https://github.com/absolut83/hw05_final) с помощью API-запросов, используя текстовый формат обмена данными, JSON, основанный на JavaScript.

Как запустить проект:
- Клонировать репозиторий
```
git clone https://github.com/absolut83/api_final_yatube.git
```
- Перейти в него:
```
cd api_final_yatube
```
- Cоздать и активировать виртуальное окружение:
```
python3 -m venv env
```
```
source env/bin/activate
```
- Установить зависимости из файла requirements.txt:
```
pip install -r requirements.txt
```
- Выполнить миграции:
```
python3 manage.py migrate
```
- Запустить проект:
```
python3 manage.py runserver
```
По адресу http://127.0.0.1:8000/redoc/ будет доступна документация для API Yatube. В документации описано, как должен работать API.

В данном проекте отсутствует фронтенд и view-функции приложения posts: для выполнения финального проекта они не понадобились.

## Об авторе
### Виталий Яремчук

absolut83@mail.ru

Telegram - @kuvalda684

