FROM openjdk:8-jdk-alpine
ARG JAR_FILE=target/*.jar
COPY com.web.app-0.0.1-SNAPSHOT.war app.jar
ENTRYPOINT ["java","-jar","/app.jar"]
