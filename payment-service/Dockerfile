FROM openjdk:17-oracle
COPY build/libs/*.jar app.jar
EXPOSE 8091
ENTRYPOINT ["java", "-jar", "app.jar"]