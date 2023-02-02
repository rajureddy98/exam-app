FROM openjdk:8-jdk-alpine

ARG JAR_FILE

COPY target/*.jar answer-servicer.jar

ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/answer-service.jar"]
