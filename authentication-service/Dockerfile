FROM openjdk:11
EXPOSE 2000
ADD target/authentication-service.jar authentication-service.jar
ENTRYPOINT ["java","-jar","/authentication-service.jar"]