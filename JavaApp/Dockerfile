# Use a base image with JDK
FROM openjdk:21-jdk-slim
# Set the working directory in the container
WORKDIR /app
# Copy the application JAR file into the container
COPY target/JavaApp-1.0-SNAPSHOT.jar app.jar
# Run the application
ENTRYPOINT ["java", "-jar", "app.jar"]
