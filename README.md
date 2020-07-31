#Homework_03
Написать приложение на Java и выложить его в новый репозиторий. Оно должно:

1) Cоздавать Excel файл
2) В файле содержится один лист с таблицей, в которой сгенерены данные для 1-30 человек (количество берется определяется в программе рандомно). Все текстовые данные на русском языке
3) Заголовки таблицы - название данных пользователей. Порядок заголовков:
Имя, фамилия, отчество, возраст, пол (М или Ж), дата рождения, Инн, почтовый индекс, страна, область, город, улица, дом, квартира
4) Добавить в проект файлы формата .txt в папку resources для генерации следующих атрибутов: Имя, фамилия, отчество, Страна, область, город, улица. 
Каждый файл должен содержать список значений, которые будут использоваться для заполнения таблицы. Для каждого атрибута отдельный файл.
Пример: вы создали файл «Countries.txt», внутри него информация выглядит
Россия
Белорусь
США
Китай
Индия
...
Количество значений в файле - не менее 30. Адрес, который вы генерите может быть несуществующим.
5) Имя, Фамилия и Отчество должны соответствовать полу. Для каждого пола можно создавать отдельные файлы с атрибутами.
6) С датой работать в формате даты (Date, DateTime и т.д.), перевести в строку только для записи в файл в формат: “ДД-ММ-ГГГГ“. Возраст должен считаться исходя из даты рождения.
7) ИНН генерить для физического лица для региона 77. Инн должен быть валидным.
8) Индекс - рандомное значение в диапазоне от 100000 до 200000
9) После того, как файл создан, в лог должно быть выведено сообщение:
“Файл создан. Путь: *здесь выводим полный путь к файлу*”
10) Создать кроме Excel-файла еще PDF-файл. Просто экспорт excel в pdf нельзя. Также вывести в лог сообщение о создании файла и для PDF. Строки в PDF можно не нумеровать
