FROM openjdk:8u252-jdk
COPY ./target/Ecom-Product-Microservice-0.0.1-SNAPSHOT.jar /
COPY ./run.sh /
EXPOSE 8084
CMD ["/bin/bash","-c","chmod +x /run.sh && /run.sh"]