# Use an official OpenJDK runtime as a parent image
FROM openjdk:11-jre-slim

# Set the working directory inside the container
WORKDIR /app

# Copy the jar file from the host machine to the container
COPY ../../../target/coursework project- 0.0.1- SNAPSHOT.jar ./

# Run the jar file
ENTRYPOINT ["java", "-jar", "/app/coursework project- 0.0.1- SNAPSHOT.jar "]
