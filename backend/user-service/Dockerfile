FROM openjdk:8-jdk-alpine

ARG JAR_FILE

COPY target/*.jar user-service.jar

ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/user-service.jar"]
