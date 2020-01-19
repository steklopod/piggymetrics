FROM openjdk:11.0.5-jre-slim
ADD ./target/registry.jar /app/
CMD ["java", "-jar", "/app/registry.jar"]
EXPOSE 8761
