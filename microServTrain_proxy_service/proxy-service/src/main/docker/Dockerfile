FROM openjdk:8-jdk-alpine
VOLUME /tmp
COPY proxy-service-0.0.1-SNAPSHOT.jar app.jar
ENV CONFIG_SERVICE "http://config-service:8888"
ENV DISCOVERY_SERVICE "http://discovery-service:8761/eureka"
ENV PRODUCT_SERVICE "http://product-service:8080/"
ENTRYPOINT ["java","-jar","/app.jar"]