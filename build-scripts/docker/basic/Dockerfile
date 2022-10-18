FROM openjdk:11

# Set default timezone
ENV TZ=Europe/Moscow
ENV SERVER_PORT 8888

ARG JAR_FILE
ADD ${JAR_FILE} /opt/app.jar

ENTRYPOINT ["java", "-jar", "/opt/app.jar"]

