# pulling a base image 
FROM openjdk:17-jdk-alpine

# creating a container or folder
WORKDIR /app

# copying the path from src to app
COPY src/Main.java /app/Main.java

# Compilen the Main.java file
RUN javac Main.java

# run the application
CMD ["java","Main"]



