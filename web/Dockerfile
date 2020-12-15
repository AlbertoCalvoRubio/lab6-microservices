FROM openjdk:8-jdk-alpine
WORKDIR /app
COPY /build/libs/web.jar .
ENTRYPOINT ["java", "-jar", "web.jar"]