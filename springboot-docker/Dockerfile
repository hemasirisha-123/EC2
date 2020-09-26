FROM openjdk:latest

ADD target/spring-boot-docker.jar spring-boot-docker.jar
WORKDIR /opt/spring-boot-docker
ENTRYPOINT ["java","-jar","/spring-boot-docker.jar"]

EXPOSE 8080