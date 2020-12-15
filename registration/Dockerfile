FROM openjdk:8-jdk-alpine
WORKDIR /app
COPY /build/libs/registration.jar .
ENTRYPOINT ["java", "-jar", "registration.jar"]