# Сайт-парсер художественных книг с сайта book24 на фреймворке Flask

Веб-приложение, которое позволяет спарсить определенное (на выбор пользователя) кол-во страниц с художественными книгами с сайта book24 (название, автор, описание, ISBN) 

Для работы сайта нужно:

1. Создать виртуальную среду 

        $ python -m venv env

2. Чтобы активировать виртуальную среду с именем env, используйте следующие команды:

        в Windows — env\Scripts\activate.bat

        в Linux и MacOS — source env/bin/activate

        Чтобы деактивировать введите deactivate

3. Установите следующие библиотеки

        $ pip install scrapy - библиотека автоматизирующая процесс парсинга.

        $ pip install flask – фреймворк для бэкенда приложения.

        $ pip install jsonlines - библиотека для обработки jsonl файлов генерируемых парсером.


4. Запустить файл который поможет нам запустить сервер Flask

        $ python app.py   

## Зависимости:
  + Python
  + Scrapy
  + Flask
  + jsonlines
