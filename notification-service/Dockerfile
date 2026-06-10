FROM gradle:8.14-jdk21 AS build
WORKDIR /app
COPY . .
RUN gradle :notification-service:bootJar --no-daemon

FROM amazoncorretto:21-alpine
WORKDIR /app
COPY --from=build /app/notification-service/build/libs/*.jar app.jar
ENTRYPOINT ["java", "-jar", "app.jar"]
