![image](https://user-images.githubusercontent.com/108483201/213289469-8383453d-5f41-40b6-b6d7-68245b4d57ef.png)


# Сквозная задача
Необходимо реализовать консольное приложение, которое:

Читает данные из входного файла;
Обрабатывает полученную информацию;
Записывает данные в выходной файл;
Входной и выходной файл могут быть следующих форматов: plain text, xml, json. Так же входные и выходные файлы могут быть архивированы и зашифрованы (только архивирован, только зашифрован, сперва архивирован, а потом зашифрован и наоборот).

«Тип» входного и выходного файла задаются параметрами консоли. Приложение реализовать двумя способами: без использования Design Patterns и c использованием Design Patterns (Decorator и Builder … можно оформить Builder в виде Singleton-а), сравнить реализации.

Обработка информации на первом этапе: найти все арифметические операции во входном файле и заменить на результаты в выходном файле. Реализовать фильтрацию двумя способами без использования регулярных выражений и с использованием регулярных выражений. Провести сравнительный анализ 2-х вариантов реализации.

# Атомарные задачи
+ Чтение \ запись текстовый файл;
+ Чтение \ запись xml файл (используя специальный API для чтения XML и не используя – чтение по строчно);
+ Чтение \ запись json файл (используя специальный API для чтения XML и не используя – чтение по строчно);
+ Архивация \ де Архивация файла используя ту или иную реализацию Zip;
+ Архивация \ де Архивация файла используя ту или иную реализацию Rar;
+ Шифровка \ де Шифровка файла используя любую библиотеку шифрования;
+ Покрыть все эти атомарные задачи Unit Test-ами;
