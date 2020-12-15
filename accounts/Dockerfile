FROM openjdk:8-jdk-alpine
WORKDIR /app
COPY /build/libs/accounts.jar .
ENTRYPOINT ["java", "-jar", "accounts.jar"]