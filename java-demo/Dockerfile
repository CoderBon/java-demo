FROM openjdk8:jdk-slim
LABEL maintainer=xiaoluo

COPY target/*.jar /app.jar

ENTRYPOINT ["java","-jar","/app.jar"]