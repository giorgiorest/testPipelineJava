FROM eclipse-temurin:21-jdk
COPY ./java-pipeline/target/*.jar /app.jar
EXPOSE 8080
ENTRYPOINT ["java","-jar","/app.jar"]