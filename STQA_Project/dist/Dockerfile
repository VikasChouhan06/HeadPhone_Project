# Use an official OpenJDK runtime as a parent image
FROM openjdk:17-jdk

# Set the working directory inside the container
WORKDIR /usr/src/app

# Copy the local JAR file (compiled Java application) to the container
COPY target/your-app.jar app.jar

# Expose the port (change as per your application)
EXPOSE 8080

# Command to run the application
CMD ["java", "-jar", "app.jar"]
