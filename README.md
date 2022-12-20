# Сайт-парсер художественных книг с сайта book24

Веб-приложение, которое позволяет спарсить определенное кол-во страниц с художественными книгами с сайта book24 (название, автор, описание, ISBN) 

Для работы сайта нужно:

1. Создать виртуальную среду 
        python -m venv env
2. Чтобы активировать виртуальную среду с именем env, используйте следующие команды:
        env\Scripts\activate.bat
        Чтобы деактивировать введите deactivate
3. Установите следующие библиотеки
        pip install scrapy - библиотека автоматизирующая процесс парсинга.
        pip install flask – фреймворк для бэкенда приложения.
        pip install jsonlines - библиотека для обработки jsonl файлов генерируемых парсером.
4. Запустить файл который поможет нам запустить сервер Flask
        python app.py   
