FROM eclipse-temurin:8-jdk-focal

WORKDIR /app

ADD target/product-service-1.0.0-SNAPSHOT.jar product-service.jar

EXPOSE 8080

ENTRYPOINT ["java","-jar", "product-service.jar"]