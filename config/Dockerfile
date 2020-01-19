FROM openjdk:11.0.5-jre-slim
USER root
WORKDIR /app
COPY ./target/config.jar ./app.jar
CMD ["java", "-jar", "app.jar"]
