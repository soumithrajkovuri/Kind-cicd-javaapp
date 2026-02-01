FROM eclipse-temurin:17-jdk-alpine

WORKDIR /java-app

COPY target/demo-1.0.jar java-app.jar

EXPOSE 8000

ENTRYPOINT ["java","-jar","java-app.jar"]