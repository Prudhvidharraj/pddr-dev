# Use OpenJDK 17 image as base
FROM openjdk:17-jdk-slim

# Set the working directory in the container
WORKDIR /app

# Copy the built jar file into the container
COPY target/prudhvi-boot-1.0-SNAPSHOT.jar /app/prudhvi-boot.jar

# Expose port 8080 to access the application
EXPOSE 8080

# Command to run the application
ENTRYPOINT ["java", "-jar", "prudhvi-boot.jar"]

