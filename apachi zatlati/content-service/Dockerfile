FROM eclipse-temurin:8-jdk-focal

WORKDIR /app

ADD target/content-service-1.0.0-SNAPSHOT.jar content-service.jar

EXPOSE 8080

ENTRYPOINT ["java","-jar", "content-service.jar"]