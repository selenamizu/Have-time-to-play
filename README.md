 Have-time-to-play
 Ноутбук загружается, библиотеки (pandas, numpy)
 необходимо загрузить данные в формате РЖД в рабочую папку (или изменить ссылку в ноутбуке соответственно
 после выполнения ноутбука будут выведены на экран результаты вычислений, а также начальные и конечные ситуации по станциям. 
 Также будет выгружен файл output.csv, который выводится на экран front-end и может быть подгружен в систему для распечатки/проверки

Архив hackatonTables - это директория веб-приложения на Flask.
Чтоб запустить приложение достаточно в редакторе кода открыть app.py и запустить в интерпритоторе.
Далее перейти на http://127.0.0.1:5000/ и увидеть как подгрузился интерфейс.
HTML + CSS выступает в роли статичного веб интерфейса, app.py подргружает данные из CSV файла, кототрый является результатом работы модели.
В зависимости от содержимого таблицы CSV будет выведен разный результат.
