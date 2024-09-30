FROM openjdk:17-oracle
COPY build/libs/*.jar app.jar
EXPOSE 8092
ENTRYPOINT ["java", "-jar", "app.jar"]