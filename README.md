# spring-boot-crud-example

=======================
Building jar file command - mvn -DMYSQL_DB_URL=jdbc:mysql://localhost:3306/test?serverTimezone=UTC -DMYSQL_DB_USER=root -DMYSQL_DB_PASSWORD=Cerebrone@2022 clean install

Run application locally in IntelliJ - 
    - Create new configuration and pass this string in the environment variables section, 
    - MYSQL_DB_URL=jdbc:mysql://localhost:3306/test?serverTimezone=UTC;MYSQL_DB_USER=root;MYSQL_DB_PASSWORD=Cerebrone@2022

Command to run the generated jar file -
java -jar target/spring-boot-crud-example.jar --MYSQL_DB_URL=jdbc:mysql://localhost:3306/test?serverTimezone=UTC --MYSQL_DB_USER=root --MYSQL_DB_PASSWORD=Cerebrone@2022