# But make sure to use the correct version of Java
FROM adoptopenjdk/openjdk8:alpine-jre

# Specify the path to the generated JAR file in the target directory
ARG artifact=target/spring-boot-web.jar

WORKDIR /opt/app

# Copy the generated JAR file into the container
COPY ${artifact} app.jar

# Set the entry point to run the Java application
ENTRYPOINT ["java","-jar","app.jar"]

