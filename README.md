# Parsing
Методы сбора и обработки данных из сети Интернет

Lesson 1: **Основы клиент-серверного взаимодействия. Парсинг API**

[Homework 1](https://github.com/PosyaginK/Parsing/blob/master/HW_1/homework_1.ipynb):
  1. Посмотреть документацию к API GitHub, разобраться как вывести список репозиториев для конкретного пользователя, сохранить JSON-вывод в файле *.json.
  2. Изучить список открытых API. Найти среди них любое, требующее авторизацию (любого типа). Выполнить запросы к нему, пройдя авторизацию. Ответ сервера записать в файл.

Lesson 2: **Парсинг HTML. BeautifulSoup, MongoDB**

[Homework 2](https://github.com/PosyaginK/Parsing/blob/master/HW_2/task_2.ipynb):

Вариант 1

Необходимо собрать информацию о вакансиях на вводимую должность (используем input или через аргументы) с сайтов Superjob и HH. Приложение должно анализировать несколько страниц сайта (также вводим через input или аргументы). Получившийся список должен содержать в себе минимум:

    Наименование вакансии.
    Предлагаемую зарплату (отдельно минимальную и максимальную).
    Ссылку на саму вакансию.
    Сайт, откуда собрана вакансия. ### По желанию можно добавить ещё параметры вакансии (например, работодателя и расположение). Структура должна быть одинаковая для вакансий с обоих сайтов. Общий результат можно вывести с помощью dataFrame через pandas.

Lesson 3: **Системы управления базами данных MongoDB и SQLite в Python**

[Homework 3](https://github.com/PosyaginK/Parsing/tree/master/HW_3):

1. Развернуть у себя на компьютере/виртуальной машине/хостинге MongoDB и реализовать функцию, записывающую собранные вакансии в созданную БД.

2. Написать функцию, которая производит поиск и выводит на экран вакансии с заработной платой больше введённой суммы.

3. Написать функцию, которая будет добавлять в вашу базу данных только новые вакансии с сайта.
