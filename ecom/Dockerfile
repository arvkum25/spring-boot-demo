# Use a smaller base image
FROM openjdk:17-jdk-alpine
# Set the working directory to /app
WORKDIR /app
# Copy the JAR file into the container
COPY target/*.jar app.jar
# Expose port 5000 (assuming that's the port your app is running on)
EXPOSE 5000
# Start the application when the container launches
CMD ["java", "-jar", "app.jar"]