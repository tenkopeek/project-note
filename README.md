# Викторина на PyQt
## Описание
Эта программа представляет собой интерактивную викторину, в которой пользователь может выбирать разные категории вопросов и отвечать на них. Вопросы и ответы хранятся в базе данных SQLite. Интерфейс викторины реализован с помощью библиотеки PyQt.
## Особенности
1. Выбор викторин: пользователь может выбрать файл с викториной.
2. Картинки к вопросам: программа берёт вопросы из базы и сопровождает их картинками.
3. Результаты: после решения викторины выводится итоговый балл и комментарий к нему.
## Технические детали
* Язык программирования: Python
* Викторины: выполнены в виде zip-архива с файлом INFO с параметрами викторины, базу данных questions.db с вопросами и папку resources с изображениями для викторины. Викторина распаковыватся во временную папку.
* Графический интерфейс: PyQt для создания оконного интерфейса.
Использованные библиотеки: pyqt5, tempfile, zipfile, sqlite
