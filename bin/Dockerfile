FROM eclipse-temurin:17.0.3_7-jdk-alpine
VOLUME /tmp
ARG JAR_FILE
COPY target/Banking-0.0.1.jar app.jar
ENTRYPOINT ["java","-jar","/app.jar"]