FROM openjdk:17-alpine
ARG JAR_FILE=..\..\services\msUser\targets\*.jar
COPY ${JAR_FILE} app.jar
ENTRYPOINT ["java","-jar","/app.jar"]