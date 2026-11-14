FROM eclipse-temurin:17-jre
VOLUME /tmp
WORKDIR /
ARG JAR_FILE=target/demo-0.0.1.jar
ADD ${JAR_FILE} app.jar
EXPOSE 8081
ENTRYPOINT ["java","-jar","/app.jar"]
