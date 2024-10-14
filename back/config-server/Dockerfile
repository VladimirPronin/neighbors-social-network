FROM openjdk:17-jdk-slim

WORKDIR /app

COPY build/libs/config-server.jar config-server.jar

ENTRYPOINT ["java", "-jar", "config-server.jar"]
