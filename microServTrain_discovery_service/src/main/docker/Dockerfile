FROM openjdk:8-jdk-alpine
VOLUME /tmp
COPY discovery-service-0.0.1-SNAPSHOT.jar app.jar
ENV DISCOVERY_SERVICE "http://config-service:8888"
ENTRYPOINT ["java","-jar","/app.jar"]