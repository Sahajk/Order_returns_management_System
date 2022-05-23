FROM openjdk:11
EXPOSE 8083
ADD target/packaging-service.jar packaging-service.jar
ENTRYPOINT ["java","-jar","/packaging-service.jar"]