# Use Java 17 base image instead of Java 11
FROM eclipse-temurin:17-jre-alpine

# Artifact path (no need to change)
ARG artifact=target/spring-boot-web.jar

WORKDIR /opt/app

COPY ${artifact} app.jar

ENTRYPOINT ["java", "-jar", "app.jar"]

