FROM openjdk:8u252-jdk
COPY ./target/Ecom-Product-Microservice-0.0.1-SNAPSHOT.jar .
EXPOSE 8888
CMD ["/bin/bash","-c","java -Dserver.port=8888 -Dspring.application.name=productservice -jar ./Ecom-Product-Microservice-0.0.1-SNAPSHOT.jar"]