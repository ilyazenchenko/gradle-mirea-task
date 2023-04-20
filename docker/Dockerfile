#версия java
FROM openjdk:18

#скопировать my-app.jar в app.jar
COPY my-app.jar app.jar

#назначаем порт 8080
EXPOSE 8080

#точка входа – файл app.jar
ENTRYPOINT ["java","-jar","app.jar"]