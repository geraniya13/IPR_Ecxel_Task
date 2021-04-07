# IPR_Java_Task
Необходимо выполнить следующее:
1. Разбить имеющийся файл на несколько файлов (5-10 файлов) и залить в одну папку.
2. Написать парсер логов, который выполняет следующие действия над логами в п.1:
   а) С помощью регулярного выражения задать фразу поиска и все найденные строки записать в новый файл
   б) Вставить разделитель ";"  между значениями в строке во всем файле, например, 17.11.2014;11:43:51.347;TRACE:;9.6.25.83:54650;Count is 1157, и записать в новый файл с расширением csv 

В результате должно быть 3 jar файла, которые будут запускаться из командной строки при помощи команды "java -jar <название jar-файла> <входные параметры>.
Входные параметры:
п.1. 2 параметра: <путь_до_лог_файла>,<постоянная_часть_имени_полученных_файлов> 
п.2. а) 3 параметра: <фраза_поиска>,<путь_до_лог_файла>,<имя_нового_файла>
     б) 3 параметра: <тип_разделителя>,<путь_до_лог_файла>,<имя_нового_файла>
