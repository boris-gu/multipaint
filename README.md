# multipaint

![example1](image/img.png)

### Компиляция и создание JAR-файла
mvn package

### Запуск
Сначала запускается сервер, он выдаст порт на котором будет работать.  
Используйте этот порт при запуске клиентов.

СЕРВЕР  
java -jar [название JAR-файла] -s

КЛИЕНТ  
java -jar [название JAR-файла] -c [адрес] [порт]
