# pm

==== WEB ====

=== Формирование ini файлов ===

Формирует ini файлы в корне проекта, пример имени файла pm1.ini (pm - обязательная часть имени, 1 - номер подсети филиала (динамическое формирование), .ini - расширение файла)

=== Структкра ini файла ===

[pm1]\\
	point = 1\\
	mode = 1\\
	logdate = 20171010.log\\

[pm1] - название раздела
point = 1 - номер подсети филиала
mode = 1 - Режим работы для программы на Autolit
logdate = 20171010.log - Название последнего лога в каталоге ПМ (за текущий день)


** !!! ВНИМАНИЕ !!! ВРЕМЯ ЖИЗНИ ФАЙЛА INI СОСТАВЛЯЕТ 3 СЕКУНДЫ !!! **

=== Режимы работы ===

1 - Перезагрузка ПМ
2 - Чтение последнего лога использовать совместно с logdate
