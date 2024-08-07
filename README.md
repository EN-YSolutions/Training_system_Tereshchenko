# Модуль главной страницы для Образовательного портала

## Инструкция по запуску на Windows

1. Установите Python 3.10.11 или более поздние версии
2. Создайте виртуальное окружение (venv) и активируйте его

```shell
python -m venv .venv
source .venv/bin/activate
```

3. Задайте переменные окружения `SECRET_KEY` и `SQLALCHEMY_DATABASE_URI` в командной строке или напрямую в файле `.env`

4. Установите зависимости

```shell
pip install -r requirements.txt
```

5. Запуск приложения

```shell
python app.py
```

### Скриншоты

![Главная страница](static/main.png "Главная страница")
