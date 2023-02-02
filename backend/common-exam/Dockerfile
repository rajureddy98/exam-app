FROM openjdk:8-jdk-alpine

ARG JAR_FILE

COPY target/*.jar common-exam.jar

ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/common-exam.jar"]
