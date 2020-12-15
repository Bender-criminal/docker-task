FROM bellsoft/liberica-openjdk-alpine:latest

COPY build/libs/admin-server-0.0.1-SNAPSHOT.jar server.jar

ENTRYPOINT ["java", "-jar", "server.jar"]

EXPOSE 9003