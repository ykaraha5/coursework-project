# Use an official OpenJDK runtime as a parent image
FROM openjdk:11-jre-slim

# Set the working directory
WORKDIR /application

# Copy the jar file into the container
COPY ../../../target/coursework project-0.0.1-SNAPSHOT.jar ./

# Run the jar file
ENTRYPOINT ["java", "-jar", "coursework project-0.0.1-SNAPSHOT.jar"]
