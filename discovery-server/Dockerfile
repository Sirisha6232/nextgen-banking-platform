FROM eclipse-temurin:21-jdk-alpine
ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} /app/app.jar
WORKDIR /app
EXPOSE 8761
ENTRYPOINT ["java","-jar","/app/app.jar"]

