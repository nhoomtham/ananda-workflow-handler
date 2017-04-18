# FROM gcr.io/google_appengine/openjdk

FROM openjdk:8-jre-alpine
VOLUME /tmp
ADD ananda-workflow-handler-1.0.0-SNAPSHOT.jar app.jar
CMD [ "java","-Dspring.profiles.active=dev","-jar","/app.jar"]