# SQL
### Порядок установки
1. Скачать проект по ссылке: https://github.com/Ufimskii/AT_3_2.git
2. Установить Java 11
3. Скачать и установить Docker Desktop
### Запуск
1. Запустить Docker контейнер. База данных MySQL. docker-compose up
2. Запустить SUT. java -jar artifacts/app-deadline.jar -P:jdbc.url=jdbc:mysql://localhost/mysql -P:jdbc.user=root -P:jdbc.password=qwerty123 .
3. Запустить автотесты. gradlew clean test.
Ожидаемый результат: BUILD SUCCESSFUL.
