FROM openjdk:11
EXPOSE 8086
ADD target/payment-service.jar payment-service.jar
ENTRYPOINT ["java","-jar","/payment-service.jar"]