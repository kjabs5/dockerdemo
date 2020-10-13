FROM openjdk:8u265-jdk-buster

MAINTAINER "Kishor limbu"

WORKDIR /usr/local/bin/

COPY ./target/dockerdemo-0.0.1-SNAPSHOT.war dockerapp.war

EXPOSE 8080

CMD ["java", "-jar","dockerapp.war"]

