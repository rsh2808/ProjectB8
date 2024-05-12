FROM ubuntu:20.04
RUN apt-get update
RUN apt-get install -y openjdk-17-jdk
COPY target/backend-1.0-RELEASE.jar .
EXPOSE 8080
CMD["java" , "-jar" , "backend-1.0-RELEASE.jar" ]
