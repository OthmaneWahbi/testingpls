FROM eclipse-temurin:8-jdk-focal

WORKDIR /app

ADD target/cart-service-1.0.0-SNAPSHOT.jar cart-service.jar

EXPOSE 8080

ENTRYPOINT ["java","-jar", "cart-service.jar"]