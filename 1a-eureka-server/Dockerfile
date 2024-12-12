
FROM openjdk:8u131-jdk-alpine
EXPOSE 7000
COPY ./target/eureka.jar eureka.jar
ENTRYPOINT ["java","-jar","/eureka.jar"]