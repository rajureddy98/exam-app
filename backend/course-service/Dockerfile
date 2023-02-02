FROM openjdk:8-jdk-alpine

ARG JAR_FILE

COPY target/*.jar course-service.jar

ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/course-service.jar"]
