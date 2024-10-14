# Используем официальный образ OpenJDK 17 с JDK
FROM openjdk:17-jdk-slim

# Устанавливаем рабочую директорию в контейнере
WORKDIR /app

# Копируем файл jar в контейнер
COPY build/libs/auth-service.jar auth-service.jar

# Указываем команду запуска приложения
ENTRYPOINT ["java", "-jar", "auth-service.jar"]
