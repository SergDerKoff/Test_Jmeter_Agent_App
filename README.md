# Test_Jmeter_Agent_App
Нагрузочные тесты для двух эндпоинтов в Jmeter

1. Установить Java: https://www.java.com/ru/download/
2. Скачать Jmeter: https://jmeter.apache.org/download_jmeter.cgi
3. Запустить файл jmeter.bat в папке `bin`
4. Открыть файл Test_Jmeter_Agent_App.jmx в Jmeter
5. Запустить тест 
6. Запуск нагрузочного теста из linux консоли (терминал):
- ввести команду -n -t ПУТЬ_ДО_/Test_Jmeter_Agent_App.jmx -l ПУТЬ_ДО_ФАЙЛА_КУДА_СОХРАНИТЬ_/Result.JTL
- смотреть результат в интерфейсе Jmeter, загрузив файл Result.JTL в блок Summary Report
