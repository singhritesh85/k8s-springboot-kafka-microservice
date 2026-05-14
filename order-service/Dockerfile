FROM eclipse-temurin:17-jdk-jammy
WORKDIR /app
COPY order-service/target/order-service-*.jar app.jar
ENTRYPOINT ["java", "-jar", "app.jar"]
