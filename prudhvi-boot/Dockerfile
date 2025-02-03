FROM openjdk:17-jdk-slim
WORKDIR /app
COPY target/prudhvi-boot-1.0-SNAPSHOT.jar /app/prudhvi-boot.jar
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "prudhvi-boot.jar"]

