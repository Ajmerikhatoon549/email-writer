# Java Runtime
FROM eclipse-temurin:21-jre

# App directory
WORKDIR /app

# Copy jar file
COPY target/email-writer-sb-0.0.1-SNAPSHOT.jar app.jar

# Railway/Render/Koyeb port support
EXPOSE 8080

# Run application
ENTRYPOINT ["java","-jar","app.jar"]
